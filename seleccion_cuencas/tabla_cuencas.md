# Cuencas con caudal observado y precipitacion diarios

Fuente: CAMELS-PE v1.0.1, archivos locales originales. Area en km2, segun topographic_attributes.csv (FABDEM v1.2).

Se evaluaron las 21 ventanas de 25 anos calendario consecutivos entre 1981 y 2025 para cada una de las 136 cuencas. Se selecciono la ventana con mayor cobertura conjunta; en empates se eligio la mas reciente. Se verifico la secuencia diaria de fechas. Un dato valido es numerico, finito y no negativo. No se imputaron datos ni se uso caudal simulado.

Caudal: flow_obs (mm/dia). Precipitacion: prec (mm/dia), producto PISCOp v2.1 promediado sobre la cuenca; no es una serie pluviometrica puntual. Cada cuenca corresponde al area aportante hasta su estacion, no necesariamente a toda la cuenca regional nombrada.

## Cumplen 25 anos sin vacios: 0

| Cuenca | Estacion | Codigo | Area (km2) | Periodo | Caudal (%) | Precipitacion (%) |
|---|---|---|---:|---|---:|---:|

Ninguna cuenca cumple el criterio estricto.

## Alternativas con al menos 95% de cobertura conjunta: 23

Este umbral es exploratorio y no equivale a 25 anos completos. Los vacios requieren evaluacion y, si procede, complementacion. La cobertura mide disponibilidad, no garantiza calidad u homogeneidad.

| Cuenca | Estacion | Codigo | Area (km2) | Periodo | Caudal (%) | Precipitacion (%) | Dias faltantes | Mayor vacio (dias) |
|---|---|---|---:|---|---:|---:|---:|---:|
| Intercuenca 49797 | Tamshiyacu | PE_240103 | 719664.668 | 1992-2016 | 99.9781 | 100 | 2 | 1 |
| Cuenca Santa | Condorcerro | PE_211408 | 10391.389 | 1988-2012 | 99.9343 | 100 | 6 | 1 |
| Intercuenca 49877 | Borja | PE_220107 | 114280.546 | 1992-2016 | 99.9014 | 100 | 9 | 9 |
| Cuenca Chancay-Lambayeque | Racarumi | PE_200907 | 2363.302 | 1997-2021 | 99.7919 | 100 | 19 | 7 |
| Intercuenca 4977 | Tabatinga | PE_2401081 | 877464.665 | 1983-2007 | 99.5181 | 100 | 44 | 11 |
| Cuenca Jequetepeque | Yonan Gore | PE_201204 | 3291.25 | 1996-2020 | 99.4744 | 100 | 48 | 4 |
| Cuenca Napo | Bellavista | PE_240111 | 99944.796 | 1992-2016 | 99.343 | 100 | 60 | 31 |
| Intercuenca Alto Huallaga | Puente Tocache | PE_47E2E456 | 23162.847 | 2001-2025 | 99.1567 | 100 | 77 | 17 |
| Cuenca Chira | El Ciruelo | PE_47E9177A | 7017.354 | 1997-2021 | 99.0034 | 100 | 91 | 11 |
| Intercuenca Ramis | Puente Ramis | PE_47251282 | 14567.21 | 1998-2022 | 98.6529 | 100 | 123 | 9 |
| Cuenca Chillón | Obrajillo | PE_47E9F488 | 371.601 | 2001-2025 | 98.2915 | 100 | 156 | 16 |
| Cuenca Tambo | Puente Santa Rosa | PE_240108 | 12824.169 | 1981-2005 | 97.6782 | 100 | 212 | 61 |
| Cuenca Tumbes | El Tigre | PE_4724A3F6 | 4733.591 | 2001-2025 | 97.514 | 100 | 227 | 20 |
| Cuenca Rímac | Chosica | PE_202906 | 2319.037 | 1999-2023 | 97.503 | 100 | 228 | 214 |
| Cuenca Chicama | El Tambo | PE_47E0A2A8 | 2171.585 | 2001-2025 | 97.273 | 100 | 249 | 20 |
| Intercuenca Alto Marañón IV | Llaucano Corellama | PE_221106 | 605.458 | 2001-2025 | 97.0102 | 100 | 273 | 13 |
| Cuenca Crisnejas | Jesus Tunel | PE_220205 | 768.505 | 1997-2021 | 96.7802 | 100 | 294 | 19 |
| Cuenca Urubamba | Egemsa Km105 | PE_4994910001 | 9581.796 | 1994-2018 | 96.4078 | 100 | 328 | 245 |
| Cuenca Chicama | Salinar | PE_211001 | 3660.362 | 1986-2010 | 95.3893 | 100 | 421 | 45 |
| Cuenca Pisco | Letrayoc | PE_213403 | 3073.563 | 1981-2005 | 95.3674 | 100 | 423 | 25 |
| Cuenca Mantaro | Puente Brena | PE_230931 | 10663.814 | 1998-2022 | 95.3455 | 100 | 425 | 26 |
| Cuenca Mantaro | Puente Stuart | PE_230906 | 9202.479 | 1981-2005 | 95.2032 | 100 | 438 | 291 |
| Intercuenca Bajo Marañón | San Regis | PE_220105 | 360046.764 | 1999-2023 | 95.0608 | 100 | 451 | 153 |
