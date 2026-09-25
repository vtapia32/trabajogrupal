Fuente de los datos

La base fue construida a partir de información pública sobre el Balón de Oro y las competiciones. Las fuentes institucionales de referencia son France Football/Ballon d'Or, UEFA y FIFA. Como apoyo para identificar posiciones históricas se pueden utilizar tablas históricas de medios y Wikipedia, siempre contrastando los datos importantes con fuentes institucionales.
France Football: https://www.francefootball.fr/ballon-d-or/palmares/
UEFA: https://www.uefa.com/ballondor/
FIFA: https://www.fifa.com/

Metodología

La unidad de observación es edición y candidato. Se registraron los tres primeros puestos de las ediciones 2000-2019 y 2021-2025. 2020 se excluye porque no hubo Balón de Oro masculino.
Los títulos se codificaron como variables binarias: 1 = el jugador obtuvo el tipo de título considerado durante el período de evaluación; 0 = no lo obtuvo. Se creó una variable derivada que suma las categorías de títulos.
No se mezclaron votos y puntos en una misma variable numérica porque el sistema de votación y la unidad publicada han cambiado. Esto evita producir comparaciones engañosas.

Alcance
La base contiene 75 observaciones: tres candidatos por cada una de las 25 ediciones con premio entre 2000 y 2025. Representa al top 3, no a todos los nominados.

Diccionario de Variables - Candidatos Balón de Oro (2000-2025)

El presente conjunto de datos analiza las características y méritos de los futbolistas nominados al Balón de Oro durante el período comprendido entre los años 2000 y 2025. A continuación, se describen detalladamente las variables que componen esta base de datos, estructuradas de forma narrativa para facilitar su comprensión e interpretación analítica.

Identificación de la Edición y el Jugador

El análisis se centra en las ediciones anuales del galardón a través de la variable Edición, registrada como un número entero que abarca los años desde el 2000 hasta el 2025 (a excepción del año 2020, edición que fue suspendida). Esta variable marca la línea temporal del evento.

Cada registro identifica a un futbolista mediante la variable Jugador, que contiene el nombre propio del candidato en formato de texto. Esta variable se limita exclusivamente a aquellos futbolistas que alcanzaron el podio del galardón, es decir, el candidato top 3 de cada entrega.

El desempeño final del jugador en la votación se mide mediante la Posición final, una variable entera que toma los valores posibles 1, 2 o 3, indicando el puesto exacto que ocupó el futbolista en el resultado del Balón de Oro de esa edición.

Contexto Deportivo y Posición en el Campo

Para contextualizar el entorno institucional del jugador durante el año de evaluación, se incluye la variable Club. Esta variable de texto registra el nombre del club al que el candidato representó, asociándolo directamente a la edición correspondiente.

En cuanto al rol táctico dentro de la cancha, la variable Posición clasifica la ubicación principal del jugador en el terreno de juego. Se trata de una variable categórica de texto cuyos valores posibles se dividen en cuatro categorías bien definidas: Delantero, Mediocampista, Defensor y Arquero.

Logros Colectivos e Indicadores de Títulos

El rendimiento colectivo de los candidatos se evalúa a través de una serie de indicadores binarios (variables enteras que toman valores de 0 para indicar ausencia y 1 para indicar presencia):

Champions League: Funciona como un indicador binario que señala si el futbolista ganó la UEFA Champions League (1) o no (0) en la temporada evaluada.

Liga nacional: Indicador binario que registra si el candidato se coronó campeón de su respectiva liga nacional (1) o no (0).

Título selección: Agrupa los mayores logros a nivel de selecciones nacionales, indicando si el jugador ganó el Mundial, la Eurocopa o la Copa América (1) o no (0), sirviendo como una variable clave para el análisis del impacto de los torneos internacionales.

Otros títulos: Indicador de carácter descriptivo que señala si el futbolista conquistó algún otro título colectivo (1) adicional a los mencionados anteriormente, o no (0).

Métrica Consolidada de Éxito

Finalmente, el conjunto de datos incorpora la variable Títulos totales, una variable derivada de tipo entero que sintetiza los logros del jugador. Sus valores posibles van del 0 al 4, contabilizando el número total de categorías de títulos colectivos que el candidato logró conquistar durante el año de la edición.
