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
  /* 
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

```
