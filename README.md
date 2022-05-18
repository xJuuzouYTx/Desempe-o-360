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
  
  // Se establece en la plantilla el objeto del usuario
  template.userInfo = userInfo;
  
  return template.evaluate()
  .setSandboxMode(HtmlService.SandboxMode.IFRAME)
  .addMetaTag("viewport", "width=device-width, initial-scale=1")
  .setFaviconUrl("https://sites.google.com/a/sinova.co/repositorio/sinova/Favicon-Evaluaci%C3%B3n-de-desempe%C3%B1o.png")
  .setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL)
  .setTitle("Evaluación de desempeño - Versión Estándar");
```
