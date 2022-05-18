# Desempe-o-360
```js

function doGet(e) {
  var template = HtmlService.createTemplateFromFile("Html_Index");
  
  // Se invoca la función que referencia las variables globales del aplicativo
  var resources = getResourcesApplication_();
  
  // Se invoca la función que consulta la información del usuario
  var userInfo = getAccountUserPanel(resources.email, "Usuario", true);
  

  // Se combina el objeto de información del usuario con el objeto del segundo parámetro
  combineObject_(userInfo, {
    isAdmin: false, // Es usuario administrador
    isLeader: false // Es líder
  }, true);

   /* UserInfo
  { 
    email: 'proyectos@sinova.co',
    name: 'Proyectos',
    shortName: 'Proyectos',
    photoUrl: 'https://www.google.com/s2/photos/public/AIbEiAIAAABDCPOYwJXwqenZTyILdmNhcmRfcGhvdG8qKDY0NDM4ZTBjYjM4OTM1MWM2MzFlMDczMDU4NmNiYjEwMzM1NDY4MTIwAaZungpSOoMO-W3xF8PLGuftDJ6H',
    isAdmin: false,
    isleader: false
  }
   */

  // Se invoca la función que valida los roles de usuario en el aplicativo (Administrador y Jefe Inmediato)
  validateUserApplication_(userInfo, resources);
  /* UserInfo
  { 
    email: 'proyectos@sinova.co',
    name: 'Proyectos',
    shortName: 'Proyectos',
    photoUrl: 'https://www.google.com/s2/photos/public/AIbEiAIAAABDCPOYwJXwqenZTyILdmNhcmRfcGhvdG8qKDY0NDM4ZTBjYjM4OTM1MWM2MzFlMDczMDU4NmNiYjEwMzM1NDY4MTIwAaZungpSOoMO-W3xF8PLGuftDJ6H',
    isAdmin: true,
    isLeader: false,
    admissionDate: '',
    area: '',
    charge: '' 
  }
  */

 // Se valida si el usuario es Administrador
  if (userInfo.isAdmin) {
    // Se establece la propiedad de la URL de la hoja de administración
    userInfo.adminSpreadsheetURL = "https://docs.google.com/spreadsheets/d/"+resources.adminSpreadsheetId;
  }
  
  // Se establece en la plantilla el texto de la fecha de vencimiento
  template.trialMessage = userInfo.expiredText || "";
  /* template.trialMessag = undefined */
  // Se establece en la plantilla el objeto del usuario
  template.userInfo = userInfo;
  
  return template.evaluate()
  .setSandboxMode(HtmlService.SandboxMode.IFRAME)
  .addMetaTag("viewport", "width=device-width, initial-scale=1")
  .setFaviconUrl("https://sites.google.com/a/sinova.co/repositorio/sinova/Favicon-Evaluaci%C3%B3n-de-desempe%C3%B1o.png")
  .setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL)
  .setTitle("Evaluación de desempeño - Versión Estándar");
```

### StartApplication() - GS_Evaluations.gs - getEvaluationInfo()
```js
 // Se invoca la función que valida la información del usuario en la hoja de administración
    consultUsersEvaluation_(adminSpreadsheet, params, resources.usersSheetName, usersListData);}
    /* params
    { userEmail: 'proyectos@sinova.co',
      userInfo: { 
        subalterns: { 'hugo.gonzalez@sinova.co': [Object] },
        name: 'Proyectos',
        email: 'proyectos@sinova.co',
        admissionDate: '01/07/2014',
        area: 'Gerencia',
        charge: 'Director' } 
      }
     */
     
      // Se invoca la función que consulta la información de evaluaciones
    consultEvaluationInfo_(adminSpreadsheet, params, resources.evaluationsSheetName);
     /* 
     { 
     userEmail: 'proyectos@sinova.co',
  userInfo: 
   { subalterns: { 'hugo.gonzalez@sinova.co': [Object] },
     name: 'Proyectos',
     email: 'proyectos@sinova.co',
     admissionDate: '01/07/2014',
     area: 'Gerencia',
     charge: 'Director' },
  evaluation: 
   { state: 'opened',
     index: 2,
     name: 'SNVA - Evaluación 2020',
     openDate: '14/08/2020',
     closeDate: '',
     resultsSpreadsheetId: '1pkJH0V7fKJqQPaVZ79V9lRS3b7nVx97-_AkvCSNFboM' } }
     */
     
     // Se valida si existe el objeto de la evaluación
    if (params.evaluation) {
      // Se valida si la evaluación aun se encuentra abierta, para posteriormente consultar la información respectiva
      if (params.evaluation.state == "opened") {
        // Se invoca la función que obtiene la escala de calificación
        consultRatingScale_(adminSpreadsheet, params, resources.ratingScaleSheetName);
        /*
        "ratingScale":{
          "1":"Nunca",
          "2":"Casi nunca",
          "3":"A veces",
           "4":"Casi siempre",
          "5":"Siempre"
        },*/
        // Se invoca la función que consulta los indicadores de evaluación
        consultIndicators_(adminSpreadsheet, params, resources.indicatorsSheetName);
        /* 
        "indicators":{
   "autoevaluation":{
      "Cumplimiento":[
         "Object"
      ],
      "Liderazgo":[
         "Object"
      ],
      "Compromiso":[
         "Object"
      ],
      "Aprendizaje":[
         "Object"
      ],
      "Productividad":[
         "Object"
      ],
      "Eficacia":[
         "Object"
      ]
   },
   "subalternEvaluation":{
      "Cumplimiento":[
         "Object"
      ],
      "Liderazgo":[
         "Object"
      ],
      "Compromiso":[
         "Object"
      ],
      "Aprendizaje":[
         "Object"
      ],
      "Productividad":[
         "Object"
      ],
      "Eficacia":[
         "Object"
      ]
   },
   "leaderEvaluation":{
      "Cumplimiento":[
         "Object"
      ],
      "Liderazgo":[
         "Object"
      ],
      "Compromiso":[
         "Object"
      ],
      "Aprendizaje":[
         "Object"
      ],
      "Productividad":[
         "Object"
      ]
   },
   "pairEvaluation":{
      "Cumplimiento":[
         "Object"
      ],
      "Liderazgo":[
         "Object"
      ],
      "Compromiso":[
         "Object"
      ],
      "Aprendizaje":[
         "Object"
      ],
      "Productividad":[
         "Object"
      ],
      "Eficacia":[
         "Object"
      ]
   }
}
}
        */
      }
    }
    
     // Se valida si existe el objeto del usuario en la Hoja de Administración
    if (params.userInfo && params.evaluation) {
      // Se valida si se tiene definida la propiedad de la evaluación que actualmente se encuentra en ejecución
      if (params.evaluation.resultsSpreadsheetId) {
        try {
          // Se obtiene la hoja de resultados de la evaluaciónusando la API SpreadsheetApp
          var evaluationSpreadsheet = SpreadsheetApp.openById(params.evaluation.resultsSpreadsheetId);
          
          // Se invoca la función que consulta el resultado de la evaluación
          consultEvaluationsResult_(evaluationSpreadsheet, params, resources.resultsSheetName, usersListData);

          // Se valida si no existe el objeto de los resultados de las evaluaciones
          if (!params.evaluations) {
            // Se elimina la propiedad de la evaluación
            delete params.evaluation;
          }

        } catch (ex) {
          saveError_(ex);
        }
      }
    }
     
```
