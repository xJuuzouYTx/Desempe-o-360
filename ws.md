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

### adminNomina
params (year)

```json
{
    "success": true,
    "returnValue": {
        "bills": [
            {
                "name": "WILMAR JHOAN  ALFONSO SABOGAL",
                "folderName": "W. Jhoan Alfonso S.",
                "month": "2019-12-31T20:05:22.859Z",
                "filename": "SNVA-NOM-Desprendible122019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1pL-S5MXmIEENuCpTQ23E6S8F490i--NU/view?usp=drivesdk",
                "fileId": "1pL-S5MXmIEENuCpTQ23E6S8F490i--NU"
            },
            {
                "folderName": "Jhon E. Páez",
                "month": "2019-12-31T20:02:40.833Z",
                "filename": "SNVA-NOM-Desprendible122019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1Dq5GmUoFkOVx14WZ8BLQxf_OrMaGpYl6/view?usp=drivesdk",
                "fileId": "1Dq5GmUoFkOVx14WZ8BLQxf_OrMaGpYl6"
            },
            {
                "name": "CESAR AUGUSTO  MELLIZO CAÑON",
                "folderName": "César A. Mellizo C.",
                "month": "2019-02-07T15:34:41.955Z",
                "filename": "SNVA-NOM-Desprendible122019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1TRIiXWmedxZ7zNVRUVhxUWDAu4pYlTTf/view?usp=drivesdk",
                "fileId": "1TRIiXWmedxZ7zNVRUVhxUWDAu4pYlTTf"
            },
            {
                "name": "CESAR AUGUSTO  MELLIZO CAÑON",
                "folderName": "César A. Mellizo C.",
                "month": "2019-02-07T15:34:41.955Z",
                "filename": "SNVA-NOM-Desprendible112019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1L8-GtvcPqxcech9ASATllZe20NTyoF9W/view?usp=drivesdk",
                "fileId": "1L8-GtvcPqxcech9ASATllZe20NTyoF9W"
            },
            {
                "name": "CESAR AUGUSTO  MELLIZO CAÑON",
                "folderName": "César A. Mellizo C.",
                "month": "2019-02-07T15:34:41.955Z",
                "filename": "SNVA-NOM-Desprendible102019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1igA67futBfdDt8K43G9vw1P2pglbOOSk/view?usp=drivesdk",
                "fileId": "1igA67futBfdDt8K43G9vw1P2pglbOOSk"
            },
            {
                "name": "CESAR AUGUSTO  MELLIZO CAÑON",
                "folderName": "César A. Mellizo C.",
                "month": "2019-02-07T15:34:41.955Z",
                "filename": "SNVA-NOM-Desprendible092019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1HD5Xd6dGn9Zwi6m3FnDKOk_mwCJL0yC3/view?usp=drivesdk",
                "fileId": "1HD5Xd6dGn9Zwi6m3FnDKOk_mwCJL0yC3"
            },
            {
                "name": "CESAR AUGUSTO  MELLIZO CAÑON",
                "folderName": "César A. Mellizo C.",
                "month": "2019-02-07T15:34:41.955Z",
                "filename": "SNVA-NOM-Desprendible082019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1DlIaVPhMngTfWH3JkoIJlUyMhUXYbJjY/view?usp=drivesdk",
                "fileId": "1DlIaVPhMngTfWH3JkoIJlUyMhUXYbJjY"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible122019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1Sh19kX7QTMmQyPpSXTxT3n3LptOAJ6TA/view?usp=drivesdk",
                "fileId": "1Sh19kX7QTMmQyPpSXTxT3n3LptOAJ6TA"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible112019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1NxM0X4WokAjRLUChDGm5ON4XG_hMhMQL/view?usp=drivesdk",
                "fileId": "1NxM0X4WokAjRLUChDGm5ON4XG_hMhMQL"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible102019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1yCdt-vf5TSdJTaY2uFcHyTFkRnDtLLfJ/view?usp=drivesdk",
                "fileId": "1yCdt-vf5TSdJTaY2uFcHyTFkRnDtLLfJ"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible092019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1eB_KcU-mAfxp7Nhbd8gaDHj0rfJyZb_D/view?usp=drivesdk",
                "fileId": "1eB_KcU-mAfxp7Nhbd8gaDHj0rfJyZb_D"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible082019.pdf",
                "fileUrl": "https://drive.google.com/file/d/150cCbP3yiNszQ19io_Ge8Y3z9He47AHm/view?usp=drivesdk",
                "fileId": "150cCbP3yiNszQ19io_Ge8Y3z9He47AHm"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible072019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1bNRQoutAOiHp0RbIBh3QxKcZXh53DAKo/view?usp=drivesdk",
                "fileId": "1bNRQoutAOiHp0RbIBh3QxKcZXh53DAKo"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible062019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1npsdNigGugjqFJqgJdN6RtrM-2rCRTqG/view?usp=drivesdk",
                "fileId": "1npsdNigGugjqFJqgJdN6RtrM-2rCRTqG"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible052019.pdf",
                "fileUrl": "https://drive.google.com/file/d/159LPsu2hLk-BYcYHrBSv4XPsQy44ZAfj/view?usp=drivesdk",
                "fileId": "159LPsu2hLk-BYcYHrBSv4XPsQy44ZAfj"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible042019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1PB6UsaKVXJJT69xFxC3lIkBo72_0S-09/view?usp=drivesdk",
                "fileId": "1PB6UsaKVXJJT69xFxC3lIkBo72_0S-09"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible032019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1SiNHDSagLgsQ4vi0zQ9rCN91fLJAqAs7/view?usp=drivesdk",
                "fileId": "1SiNHDSagLgsQ4vi0zQ9rCN91fLJAqAs7"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible022019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1INayZIz_T-Xz_MmZXE3o7E9A_x8XRV4A/view?usp=drivesdk",
                "fileId": "1INayZIz_T-Xz_MmZXE3o7E9A_x8XRV4A"
            },
            {
                "name": "CARLOS ANDRES  ALMANZA TORRES",
                "folderName": "Carlos A. Almanza T.",
                "month": "2019-02-05T01:36:23.294Z",
                "filename": "SNVA-NOM-Desprendible012019.pdf",
                "fileUrl": "https://drive.google.com/file/d/0BzEiVSCzfq-XOHIxQ3JWZExaWmdfTVplckFzdVJoNzVSZ2hF/view?usp=drivesdk&resourcekey=0-bZbUYYO9fl135-trJ3UNnw",
                "fileId": "0BzEiVSCzfq-XOHIxQ3JWZExaWmdfTVplckFzdVJoNzVSZ2hF"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "Préstamo Personal DRubénS",
                "fileUrl": "https://docs.google.com/spreadsheets/d/1LQ2e61yG2hlqg-aJe0fmlH4xlgqjb6AlEcmjwEEExIU/edit?usp=drivesdk",
                "fileId": "1LQ2e61yG2hlqg-aJe0fmlH4xlgqjb6AlEcmjwEEExIU"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible122019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1RG43KTWOT2mB9iI1BPJYcFolKdaPVEUV/view?usp=drivesdk",
                "fileId": "1RG43KTWOT2mB9iI1BPJYcFolKdaPVEUV"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible112019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1nMykMNzuRoORacmpseo2ZGMJIj7a3MMo/view?usp=drivesdk",
                "fileId": "1nMykMNzuRoORacmpseo2ZGMJIj7a3MMo"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible102019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1gsHP76nokf_sv9LutJJo-zOzFbeFblrl/view?usp=drivesdk",
                "fileId": "1gsHP76nokf_sv9LutJJo-zOzFbeFblrl"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible092019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1LfB-47-Ze0JPq1XrsR17A9IWiQktEhyI/view?usp=drivesdk",
                "fileId": "1LfB-47-Ze0JPq1XrsR17A9IWiQktEhyI"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible082019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1zLo-BNx5uqFjmduVFqdcMrUMTuA5E8jF/view?usp=drivesdk",
                "fileId": "1zLo-BNx5uqFjmduVFqdcMrUMTuA5E8jF"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible072019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1s8fH_QtgO9_OFz68pwfgG_VBadXrPaS_/view?usp=drivesdk",
                "fileId": "1s8fH_QtgO9_OFz68pwfgG_VBadXrPaS_"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible062019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1r5io_dYpkyrVJDB85fTi_NE7jMTl3d-y/view?usp=drivesdk",
                "fileId": "1r5io_dYpkyrVJDB85fTi_NE7jMTl3d-y"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible052019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1EUdfH1qv1Mbi7Q1m4gQTMARlAZ2u6fIM/view?usp=drivesdk",
                "fileId": "1EUdfH1qv1Mbi7Q1m4gQTMARlAZ2u6fIM"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible042019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1u4afI7DuZDsTR4htx2gosIkIhwGDjmwU/view?usp=drivesdk",
                "fileId": "1u4afI7DuZDsTR4htx2gosIkIhwGDjmwU"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible032019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1fnt4knOlZAFl5ZSxzi5bXf6f4ecav1X2/view?usp=drivesdk",
                "fileId": "1fnt4knOlZAFl5ZSxzi5bXf6f4ecav1X2"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible022019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1-TS1SGeVAGTchHAwcquvEWg-0njpYHCt/view?usp=drivesdk",
                "fileId": "1-TS1SGeVAGTchHAwcquvEWg-0njpYHCt"
            },
            {
                "name": "RUBEN DARIO SANCHEZ RAMIREZ",
                "folderName": "Rubén D. Sánchez R.",
                "month": "2019-02-05T01:23:27.047Z",
                "filename": "SNVA-NOM-Desprendible012019.pdf",
                "fileUrl": "https://drive.google.com/file/d/0BzEiVSCzfq-XdVZmbnhDcmVjaWpzNldQcjF5QnRPcnBjN2ZR/view?usp=drivesdk&resourcekey=0-fvnBafrIfkuZ3a2BYckC3A",
                "fileId": "0BzEiVSCzfq-XdVZmbnhDcmVjaWpzNldQcjF5QnRPcnBjN2ZR"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible122019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1vfPa2BcW1KyFiuak7K7_hPmNFgY6cqFO/view?usp=drivesdk",
                "fileId": "1vfPa2BcW1KyFiuak7K7_hPmNFgY6cqFO"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible112019.pdf",
                "fileUrl": "https://drive.google.com/file/d/10qF05yrjBRvwnB2oCWof7V-dqARziUWS/view?usp=drivesdk",
                "fileId": "10qF05yrjBRvwnB2oCWof7V-dqARziUWS"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible102019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1WRzcGLQB997jhrUWkt46YnfN822VluJt/view?usp=drivesdk",
                "fileId": "1WRzcGLQB997jhrUWkt46YnfN822VluJt"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible092019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1cgi4zl8Jv-77amaZTvmdb3ydtOlsG8di/view?usp=drivesdk",
                "fileId": "1cgi4zl8Jv-77amaZTvmdb3ydtOlsG8di"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible082019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1gHJeytuPzVo1zixslO-WZsW8hA5wFarw/view?usp=drivesdk",
                "fileId": "1gHJeytuPzVo1zixslO-WZsW8hA5wFarw"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible072019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1Rx2pSTmtesWOKMZbl2AjBt4RgRooHxyy/view?usp=drivesdk",
                "fileId": "1Rx2pSTmtesWOKMZbl2AjBt4RgRooHxyy"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible062019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1kpsvuOMud9drlH17BVwXHJJHm7BexKFE/view?usp=drivesdk",
                "fileId": "1kpsvuOMud9drlH17BVwXHJJHm7BexKFE"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible052019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1LHvo6T4PQkxgIwoQrD2Ow4N20U6enN5J/view?usp=drivesdk",
                "fileId": "1LHvo6T4PQkxgIwoQrD2Ow4N20U6enN5J"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible042019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1Zg9kFh8C1YuDiElK6v4IeJgjYvDqvpFI/view?usp=drivesdk",
                "fileId": "1Zg9kFh8C1YuDiElK6v4IeJgjYvDqvpFI"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible032019.pdf",
                "fileUrl": "https://drive.google.com/file/d/126W6xcCDhzoFIty5y-xCjmC_y1ZsZ9cg/view?usp=drivesdk",
                "fileId": "126W6xcCDhzoFIty5y-xCjmC_y1ZsZ9cg"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible022019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1_mgAu2Xol_3dHyBb0cyTIV8cf4CCm2GO/view?usp=drivesdk",
                "fileId": "1_mgAu2Xol_3dHyBb0cyTIV8cf4CCm2GO"
            },
            {
                "folderName": "Arnold I. Nova R.",
                "month": "2019-02-05T01:37:07.962Z",
                "filename": "SNVA-NOM-Desprendible012019.pdf",
                "fileUrl": "https://drive.google.com/file/d/0BzEiVSCzfq-Xa1U1UUFEMS1fQzk3NlhfLUh1bHBvWW1wRG1j/view?usp=drivesdk&resourcekey=0-VGGaPFLNAx5Xss6_4wqbWA",
                "fileId": "0BzEiVSCzfq-Xa1U1UUFEMS1fQzk3NlhfLUh1bHBvWW1wRG1j"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible122019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1E-bTY8gLsQaVi4hTgGFkDZ0wtnfui8HR/view?usp=drivesdk",
                "fileId": "1E-bTY8gLsQaVi4hTgGFkDZ0wtnfui8HR"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible112019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1rC2TAKekTHWU9sHolIRnJ3vUNgMohXe6/view?usp=drivesdk",
                "fileId": "1rC2TAKekTHWU9sHolIRnJ3vUNgMohXe6"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible102019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1qoO3S1JjIbpzMqpjQLkJ1qdco-7cntUN/view?usp=drivesdk",
                "fileId": "1qoO3S1JjIbpzMqpjQLkJ1qdco-7cntUN"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible092019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1mGroD-hqe5zLf3IoVnDVUynFqxECFA68/view?usp=drivesdk",
                "fileId": "1mGroD-hqe5zLf3IoVnDVUynFqxECFA68"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible082019.pdf",
                "fileUrl": "https://drive.google.com/file/d/19IEsBZybZarrqiNYYT2Z4J7jEqyv_A9H/view?usp=drivesdk",
                "fileId": "19IEsBZybZarrqiNYYT2Z4J7jEqyv_A9H"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible072019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1f8WpolKU5TY4DSRBwDkSOODyE2_WmjGO/view?usp=drivesdk",
                "fileId": "1f8WpolKU5TY4DSRBwDkSOODyE2_WmjGO"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible062019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1z_yllrxWEDQA5Ihw3kqXhDpfnxo4bnQh/view?usp=drivesdk",
                "fileId": "1z_yllrxWEDQA5Ihw3kqXhDpfnxo4bnQh"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible052019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1LwL0n0e8BAQVsH9z1wr4G69W_Ol1BjvJ/view?usp=drivesdk",
                "fileId": "1LwL0n0e8BAQVsH9z1wr4G69W_Ol1BjvJ"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible042019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1xuNlZxf-akcXpexdsQ0Rngu2irPlc7QV/view?usp=drivesdk",
                "fileId": "1xuNlZxf-akcXpexdsQ0Rngu2irPlc7QV"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible032019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1Xjg1jWMOBJplKtZOaykprCFJxffKY4ss/view?usp=drivesdk",
                "fileId": "1Xjg1jWMOBJplKtZOaykprCFJxffKY4ss"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible022019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1z2iJdsyEIeeSIJQ4-3kICBJRIY8XmWU8/view?usp=drivesdk",
                "fileId": "1z2iJdsyEIeeSIJQ4-3kICBJRIY8XmWU8"
            },
            {
                "name": "CESAR AUGUSTO GOMEZ RODRIGUEZ",
                "folderName": "César A. Gómez R.",
                "month": "2019-02-05T01:35:15.881Z",
                "filename": "SNVA-NOM-Desprendible012019.pdf",
                "fileUrl": "https://drive.google.com/file/d/0BzEiVSCzfq-XeGhueGZER3pjS1ppY1hYQWtyV2FIOEdReDFF/view?usp=drivesdk&resourcekey=0-FeC8OapjtxuvJll4WmzLGg",
                "fileId": "0BzEiVSCzfq-XeGhueGZER3pjS1ppY1hYQWtyV2FIOEdReDFF"
            },
            {
                "name": "FELIPE ANDRES  LOPEZ MORENO ",
                "folderName": "Felipe A. López M.",
                "month": "2019-02-05T01:32:28.664Z",
                "filename": "SNVA-NOM-Desprendible042019.pdf",
                "fileUrl": "https://drive.google.com/file/d/11dG-uqm124LB02LwFHui1qDLurDNUQZH/view?usp=drivesdk",
                "fileId": "11dG-uqm124LB02LwFHui1qDLurDNUQZH"
            },
            {
                "name": "FELIPE ANDRES  LOPEZ MORENO ",
                "folderName": "Felipe A. López M.",
                "month": "2019-02-05T01:32:28.664Z",
                "filename": "SNVA-NOM-Desprendible032019.pdf",
                "fileUrl": "https://drive.google.com/file/d/1OvIHMkQxX9Ew78z9asMxzmbY-lf7Mfmp/view?usp=drivesdk",
                "fileId": "1OvIHMkQxX9Ew78z9asMxzmbY-lf7Mfmp"
            },
            {
                "name": "FELIPE ANDRES  LOPEZ MORENO ",
                "folderName": "Felipe A. López M.",
                "month": "2019-02-05T01:32:28.664Z",
                "filename": "SNVA-NOM-Desprendible022019.pdf",
                "fileUrl": "https://drive.google.com/file/d/110Pw3JLtOfyv7257b8tsqVya1yHF9eiK/view?usp=drivesdk",
                "fileId": "110Pw3JLtOfyv7257b8tsqVya1yHF9eiK"
            },
            {
                "name": "FELIPE ANDRES  LOPEZ MORENO ",
                "folderName": "Felipe A. López M.",
                "month": "2019-02-05T01:32:28.664Z",
                "filename": "SNVA-NOM-Desprendible012019.pdf",
                "fileUrl": "https://drive.google.com/file/d/0BzEiVSCzfq-XZDlGLUppNHV2M0R0MFJRQXU4cXY4eEV6R004/view?usp=drivesdk&resourcekey=0-3Na3d22bBeyTODHDZkkI6g",
                "fileId": "0BzEiVSCzfq-XZDlGLUppNHV2M0R0MFJRQXU4cXY4eEV6R004"
            }
        ],
        "rootFolder": "https://drive.google.com/drive/folders/0BzEiVSCzfq-Xfk5uV18tbXJzUWRtWkIwR3BBTE9RWlNDZ19FTXFuZ3B4MFdyQjVVb2xGV3M?resourcekey=0-VtF8QkIZf0aNW6REa0lB9Q"
    }
}
```

