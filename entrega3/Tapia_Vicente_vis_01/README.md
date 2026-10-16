# Documentación del Proceso de Visualización

## Explicación del proceso de visualización
* Se cargó y depuró el archivo `Top5_Balon_de_Oro_2000_2025.csv`, omitiendo las filas de metadatos iniciales y excluyendo el año 2020 (por cancelación debido a COVID-19) y 2025 (por estar en curso).
* Se agrupó la variable cuantitativa `Posicion` en tres categorías jerárquicas analíticas: *1º Balón de Oro*, *2º y 3º (Podio)* y *4º y 5º lugar*.
* Se transformó la columna `Champions League` en una variable booleana evaluando si el texto iniciaba con "Sí".
* Se calcularon las frecuencias absolutas y porcentuales relativas por cada grupo posicional.
* Se construyó el gráfico de barras apiladas horizontales mediante **Altair**, superponiendo capas de texto para imprimir los porcentajes exactos dentro de las barras con formato visual adaptado para webstories.

## Base de datos seleccionada y procesamiento
Se seleccionó el tramo 2000–2025 (130 registros totales) por representar la era moderna y estandarizada del galardón. Los datos fueron procesados en Python para estandarizar cadenas de texto, eliminar espacios vacíos y unificar criterios de premiación.

## Ejemplos de preguntas que responde la visualización
* **¿Qué porcentaje de ganadores del Balón de Oro en el siglo XXI conquistó la Champions League el mismo año?**  
  *Respuesta visualizada:* 41,7%.
* **¿Existe una diferencia significativa en la posesión de la Champions entre el primer lugar y los puestos 4º y 5º?**  
  *Respuesta visualizada:* sí, existe una brecha favorable de más de 8 puntos porcentuales hacia la cúspide.