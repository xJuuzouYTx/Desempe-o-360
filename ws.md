### ValidateUser()
getActiveUser()

```json
{
    "success": true,
    "returnValue": {
        "isAccess": true,
        "settingsData": {
            "idLogo": "1riYZlGaqXPmrpHe5rvJOH2k1rzWWCU-S",
            "urlLogo": "https://drive.google.com/uc?export=download&amp;id=1riYZlGaqXPmrpHe5rvJOH2k1rzWWCU-S",
            "urlBackLogin": "https://drive.google.com/uc?export=download&amp;id=1TDpp8PjckpUlntV4nTyeItSyY8LamY6O",
            "urlWorkCertificateLogo": "https://drive.google.com/uc?export=download&amp;id=1finAPyvqUy1VdugnVvHmve9jCsjdXx-W",
            "primaryColor": "#023e8a",
            "appName": "Certificado laboral - Intranet",
            "inicialWorkCertificate": "SNVA",
            "ceritificateLimit": "10",
            "templateDocWorkCertificateId": "1AJUegAbQd0ndlC4YyyXAuHrt_CJE5JgeyVDMlbmTvL4",
            "templateDocWorkCertificateIdEx": "114cJFe_2rizJdi-jUIUXMmGNhHE9CBI4gCRxMHPWJNA",
            "folderWorkCertificateId": "1KfgItLDczwFCpLRwvnalZ9yUI2CmpjOO",
            "folderIdDesprendibles": "0BzEiVSCzfq-Xfk5uV18tbXJzUWRtWkIwR3BBTE9RWlNDZ19FTXFuZ3B4MFdyQjVVb2xGV3M"
        },
        "userData": {
            "mail": "joseluis.malagon@sinova.co",
            "document": 79165931,
            "documentCustom": 79165931,
            "name": "JOSE LUIS MALAGON VILLAMIL",
            "position": "Director",
            "functions": "· Función 1\n· Función 2\n· Función 3",
            "admissionDate": "Fri Aug 01 2014 00:00:00 GMT-0500 (hora estándar de Colombia)",
            "endDate": "",
            "salary": "1500000",
            "bonus": "500000",
            "enabledCertifications": true,
            "city": "UBATE",
            "contract": "a termino indefinido",
            "rowIndex": 3,
            "maxCertifications": "10",
            "certificationsQuantity": 1,
            "folderName": ""
        },
        "admin": true,
        "availableUsers": [
            {
                "colab": "RUBEN DARIO SANCHEZ RAMIREZ",
                "document": 1076656364,
                "folderName": "Rubén D. Sánchez R."
            },
            {
                "colab": "CARLOS ANDRES  ALMANZA TORRES",
                "document": 1076660121,
                "folderName": "Carlos A. Almanza T."
            },
            {
                "colab": "CESAR AUGUSTO  MELLIZO CAÑON",
                "document": 1076649746,
                "folderName": "César A. Mellizo C."
            },
            {
                "colab": "FELIPE ANDRES  LOPEZ MORENO ",
                "document": 1076656491,
                "folderName": "Felipe A. López M."
            },
            {
                "colab": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "document": 1076659226,
                "folderName": "César A. Gómez R."
            }
        ],
        "links": {
            "internalUrl": "https://docs.google.com/document/d/1AJUegAbQd0ndlC4YyyXAuHrt_CJE5JgeyVDMlbmTvL4",
            "externalUrl": "https://docs.google.com/document/d/114cJFe_2rizJdi-jUIUXMmGNhHE9CBI4gCRxMHPWJNA",
            "sheetBaseUrl": "https://docs.google.com/spreadsheets/d/1Zi6Q26yG2AdXuqO8htB146LC6h9V9Wt4Ch0jb2-h-C8"
        }
    }
}
```

### nomina()
params({"document": "1076656364", "year": "2014", "email": "proyectos@sinova.co"})

```json
{
    "success": true,
    "returnValue": {
        "info": {
            "name": "RUBEN DARIO SANCHEZ RAMIREZ",
            "document": 1076656364,
            "email": "proyectos@sinova.co",
            "folderName": "Rubén D. Sánchez R.",
            "startDate": "Wed Oct 01 2014 00:00:00 GMT-0500 (hora estándar de Colombia)",
            "availableYears": [
                "2014",
                "2015",
                "2016",
                "2017",
                "2018",
                "2019",
                "2020",
                "2022"
            ]
        },
        "bills": [
            {
                "fileName": "SNVA-NOM-Desprendible102014.pdf",
                "creation": "15/10/2017 09:15 AM",
                "fileId": "0BzEiVSCzfq-XN0xGdGdWUW5QZm8",
                "downloadUrl": "https://drive.google.com/uc?id=0BzEiVSCzfq-XN0xGdGdWUW5QZm8&export=download",
                "month": 10,
                "monthYear": "Octubre de 2014",
                "monthName": "Octubre"
            },
            {
                "fileName": "SNVA-NOM-Desprendible112014.pdf",
                "creation": "15/10/2017 09:15 AM",
                "fileId": "0BzEiVSCzfq-XTTRjLXlPR3JlN2c",
                "downloadUrl": "https://drive.google.com/uc?id=0BzEiVSCzfq-XTTRjLXlPR3JlN2c&export=download",
                "month": 11,
                "monthYear": "Noviembre de 2014",
                "monthName": "Noviembre"
            },
            {
                "fileName": "SNVA-NOM-Desprendible122014.pdf",
                "creation": "15/10/2017 09:15 AM",
                "fileId": "0BzEiVSCzfq-XR0l4bnJ5UkdrOWc",
                "downloadUrl": "https://drive.google.com/uc?id=0BzEiVSCzfq-XR0l4bnJ5UkdrOWc&export=download",
                "month": 12,
                "monthYear": "Diciembre de 2014",
                "monthName": "Diciembre"
            }
        ],
        "months": [],
        "validEmail": true
    }
}
```

