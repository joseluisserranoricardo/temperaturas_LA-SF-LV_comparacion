# 🌡️ Análisis de Temperaturas

## 📝 Descripción
Este proyecto analiza las temperaturas extremas de las tres ciudades más famosas del oeste de EE.UU. (Los Ángeles, San Francisco y Las Vegas) durante 2012-2017.

## ⚙️ Técnicas y Herramientas Aplicadas
* **Data Cleaning & Transformation:** Procesamiento de un dataset de +45,000 registros horarios utilizando Power Query.
* **Ingeniería de Datos:** Conversión de unidades mediante la fórmula estadandard ($°C = K - 273.15$).
* **Visualización Dinámica:** Uso de Escalas de Tiempo (Timelines) para segmentar el comportamiento climático a meses, trimestres o años.

![febrero](https://github.com/user-attachments/assets/ea77eaf2-4c55-45bd-90b6-42257c8c21e8)
![trimestre](https://github.com/user-attachments/assets/b682b1de-f2ac-429a-b6be-438926302de1)

## 📊 Ejemplo de como analizar estos datos: Resultados 2017

| Ciudad | Temp. Mínima (°C) | Temp. Máxima (°C) | Variación (Delta) |
| :--- | :---: | :---: | :---: |
| **Las Vegas** | -11.65° | 45.21° | **56.86°C** |
| **Los Ángeles** | -3.54° | 39.37° | 42.91°C |
| **San Francisco** | 0.75° | 40.47° | 39.72°C |

![2017](https://github.com/user-attachments/assets/a8e3098c-b3ba-421b-8db1-22d8bfe67e29)
### 🔍 Insights Clave:
1.  **Efecto Desértico:** Las Vegas presenta la mayor amplitud térmica, con una diferencia de casi 57°C entre su punto más frío y el más cálido, validando el comportamiento climático de zonas áridas.
2.  **Estabilidad Marítima:** San Francisco, a pesar de estar más al norte, mostró la temperatura mínima más alta (0.75°C), demostrando el efecto regulador del Océano Pacífico frente a Los Ángeles.

## 📁 Estructura del Repositorio
* `temperature.csv`: Dataset original con registros históricos.
* `temperaturas LA-SF-LV comparacion.xlsx`: Archivo Final del Trabajo.
* `README.md`: Documentación del proyecto.
* `📁jpeg`: Carpeta de capturas que aparecen en el readme.
