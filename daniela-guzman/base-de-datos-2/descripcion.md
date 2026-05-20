# a) Descripción general
* **Nombre de la base de datos:** Breast Cancer Wisconsin Diagnostic.
* **¿Qué es la base de datos?:** Características geométricas de imágenes de tumores de mama para clasificar si son benignos o malignos.
* **¿Cómo se obtuvieron los datos?:** Análisis bajo microscopio y digitalización de tumores extraídos.
* **Fuente / URL:** UCI Machine Learning Repository (archive.ics.uci.edu/dataset/17).
* **Número de filas y columnas:** 569 filas y 32 columnas.
* **Formato del archivo:** CSV.

# b) Descripción de columnas
| Nombre de columna | Tipo de dato | Descripción | Ejemplo de valor |
| :--- | :--- | :--- | :--- |
| id | Numérico (int) | Número de identificación de la paciente | 842302 |
| diagnosis | Texto (str) | Diagnóstico (M=Maligno, B=Benigno) | M |
| radius_mean | Numérico (float) | Media de distancias del centro | 17.99 |
| texture_mean | Numérico (float) | Media de desviación estándar en escala de grises | 10.38 |
| perimeter_mean | Numérico (float) | Perímetro medio del núcleo tumoral | 122.8 |
| area_mean | Numérico (float) | Área media del núcleo | 1001.0 |
| smoothness_mean | Numérico (float) | Media de variación local en la longitud del radio | 0.1184 |
| compactness_mean | Numérico (float) | Compacidad media del contorno | 0.2776 |
| concavity_mean | Numérico (float) | Media de severidad de zonas cóncavas | 0.3001 |
| concave points_mean| Numérico (float) | Media del número de zonas cóncavas | 0.1471 |
| symmetry_mean | Numérico (float) | Simetría media del núcleo | 0.2419 |
| fractal_dimension_mean| Numérico (float) | Dimensión fractal media | 0.07871 |
| radius_se | Numérico (float) | Error estándar del radio | 1.095 |
| texture_se | Numérico (float) | Error estándar de la textura | 0.9053 |
| perimeter_se | Numérico (float) | Error estándar del perímetro | 8.589 |
| area_se | Numérico (float) | Error estándar del área | 153.4 |
| smoothness_se | Numérico (float) | Error estándar de la suavidad | 0.006399 |
| compactness_se | Numérico (float) | Error estándar de la compacidad | 0.04904 |
| concavity_se | Numérico (float) | Error estándar de la concavidad | 0.05373 |
| concave points_se | Numérico (float) | Error estándar de los puntos cóncavos | 0.01587 |
| symmetry_se | Numérico (float) | Error estándar de la simetría | 0.03003 |
| fractal_dimension_se| Numérico (float) | Error estándar de la dimensión fractal | 0.006193 |
| radius_worst | Numérico (float) | Peor valor (mayor) medido del radio | 25.38 |
| texture_worst | Numérico (float) | Peor valor de la textura | 17.33 |
| perimeter_worst | Numérico (float) | Peor valor del perímetro | 184.6 |
| area_worst | Numérico (float) | Peor valor del área | 2019.0 |
| smoothness_worst | Numérico (float) | Peor valor de la suavidad | 0.1622 |
| compactness_worst | Numérico (float) | Peor valor de la compacidad | 0.6656 |
| concavity_worst | Numérico (float) | Peor valor de la concavidad | 0.7119 |
| concave points_worst| Numérico (float) | Peor valor de los puntos cóncavos | 0.2654 |
| symmetry_worst | Numérico (float) | Peor valor de la simetría | 0.4601 |
| fractal_dimension_worst| Numérico (float)| Peor valor de la dimensión fractal | 0.1189 |
