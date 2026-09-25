Objetivo

La base busca permitir una comparación sistemática entre los tres primeros candidatos de cada edición del Balón de Oro entre 2000 y 2025. La estructura permite estudiar si los títulos colectivos aparecen asociados a mejores posiciones en la votación.
Fuentes

Se priorizaron France Football/Ballon d'Or para el historial del premio, UEFA para la Champions League y FIFA para los torneos de selecciones. Las fuentes secundarias se utilizarán para localizar información histórica y serán contrastadas cuando sea posible.
Decisión sobre el período

El proyecto original buscaba cubrir toda la historia del premio. La revisión metodológica mostró que las estadísticas individuales antiguas son mucho menos consistentes y que el sistema de votación cambió. Por eso se acotó esta base a 2000-2025. Esto mantiene una perspectiva histórica amplia, pero reduce el riesgo de comparar datos incompatibles.
Proceso de limpieza

Primero se definió la unidad de observación: una fila equivale a un candidato en una edición. Después se normalizaron los nombres de jugadores, clubes y posiciones. La posición final se transformó en un número entero de 1 a 3.
Luego se codificaron los títulos colectivos como variables binarias. Un 1 indica que el candidato consiguió ese tipo de título durante el período evaluado y un 0 indica que no. Las categorías fueron Champions League, título importante con la selección, liga nacional y otros títulos relevantes.
Se agregó una categoría de títulos toales para facilitar agrupaciones y visualizaciones. Esta suma no pretende establecer que una Champions equivale a una liga o a un torneo de selecciones; solo registra cuántas categorías de éxito colectivo aparecen en cada fila.
Votos y puntos

No se incluyeron votos/puntos como una variable numérica única en esta versión porque el sistema no es homogéneo durante todo el período. Cuando la investigación incorpore resultados de votación, se conservará también la unidad original (porcentaje, puntos u otra medida) y se evitará mezclar escalas.
Limitaciones

La base contiene top 3, no todos los nominados. Además, los títulos colectivos no tienen el mismo peso competitivo. La base permite estudiar asociaciones, pero no demostrar que un título causó un voto determinado.
Tampoco se incluyeron goles y asistencias como requisito, ya que la disponibilidad histórica y la comparación entre posiciones presentan problemas metodológicos. Se podrán añadir en una segunda etapa para años donde sean comparables.
Preguntas que permite responder
1.	¿Qué proporción de los ganadores del período ganó Champions?
2.	¿Cuántos segundos o terceros lugares tuvieron al menos un gran título colectivo?
3.	¿Qué excepciones existen entre éxito colectivo y posición final?
4.	¿Qué ocurre en los años con grandes torneos de selecciones?
Replicabilidad
Para repetir el proceso se parte del archivo original, se conserva una fila por edición y candidato, se normalizan los campos, se codifican los títulos en 0/1, se comprueban valores faltantes y se genera la variable derivada de categorías de títulos. Luego el CSV se puede cargar directamente en Pandas para generar tablas y visualizaciones.


