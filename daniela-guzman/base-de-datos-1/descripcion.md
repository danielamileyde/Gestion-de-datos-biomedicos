# a) Descripción general
* **Nombre de la base de datos:** Chronic Kidney Disease.
* **¿Qué es la base de datos?:** Registros clínicos para predecir si un paciente tiene enfermedad renal crónica.
* **¿Cómo se obtuvieron los datos?:** Registros administrativos hospitalarios, extracción de sangre y orina.
* **Fuente / URL:** UCI Machine Learning Repository (archive.ics.uci.edu/dataset/336).
* **Número de filas y columnas:** 400 filas y 26 columnas.
* **Formato del archivo:** CSV.

# b) Descripción de columnas
| Nombre de columna | Tipo de dato | Descripción | Ejemplo de valor |
| :--- | :--- | :--- | :--- |
| id | Numérico (int) | Identificador único del paciente | 0 |
| age | Numérico (float) | Edad del paciente en años | 48.0 |
| bp | Numérico (float) | Presión arterial en mm/Hg | 80.0 |
| sg | Numérico (float) | Gravedad específica de la orina | 1.020 |
| al | Numérico (float) | Nivel de albúmina en la orina | 1.0 |
| su | Numérico (float) | Nivel de azúcar en la orina | 0.0 |
| rbc | Texto (str) | Glóbulos rojos (normal/abnormal) | normal |
| pc | Texto (str) | Células de pus (normal/abnormal) | normal |
| pcc | Texto (str) | Cúmulos de células de pus | notpresent |
| ba | Texto (str) | Presencia de bacterias | notpresent |
| bgr | Numérico (float) | Glucosa en sangre | 121.0 |
| bu | Numérico (float) | Urea en sangre | 36.0 |
| sc | Numérico (float) | Creatinina sérica | 1.2 |
| sod | Numérico (float) | Nivel de sodio | 138.0 |
| pot | Numérico (float) | Nivel de potasio | 4.4 |
| hemo | Numérico (float) | Hemoglobina | 15.4 |
| pcv | Numérico (str) | Hematocrito | 44 |
| wc | Numérico (str) | Conteo de glóbulos blancos | 7800 |
| rc | Numérico (str) | Conteo de glóbulos rojos | 5.2 |
| htn | Texto (str) | Hipertensión | yes |
| dm | Texto (str) | Diabetes mellitus | yes |
| cad | Texto (str) | Enfermedad coronaria | no |
| appet | Texto (str) | Apetito | good |
| pe | Texto (str) | Edema pedal | no |
| ane | Texto (str) | Anemia | no |
| classification | Texto (str) | Diagnóstico | ckd |
