**Objetivo**

La base busca permitir una comparación sistemática entre los tres primeros candidatos de cada edición del Balón de Oro entre 1956 y 1999. La estructura permite estudiar si los títulos colectivos aparecen asociados a mejores posiciones en la votación durante la era clásica del galardón.

**Fuentes**

Se priorizaron France Football para el historial del premio, UEFA para las competiciones europeas de clubes (como la Copa de Campeones, actual UEFA Champions League) y FIFA junto con organismos continentales para los torneos de selecciones (como la Eurocopa y la Copa América). Las fuentes secundarias se utilizaron para localizar y contrastar información histórica de la época.

**Periodo**

El proyecto original abarcaba un espectro temporal más amplio. Se acotó esta base al período 1956-1999 para mantener una perspectiva histórica rigurosa bajo el sistema tradicional del premio: la etapa en la que el galardón estuvo restringido exclusivamente a futbolistas europeos (1956-1994) y sus primeros años de apertura global previo al siglo XXI.

**Proceso de Limpieza**

Primero se definió la unidad de observación: una fila equivale a un candidato en una edición. Después se normalizaron los nombres de jugadores, clubes, nacionalidades y posiciones en el campo. La posición final se transformó en un número entero de 1 a 3 (podio).

Luego se codificaron los títulos colectivos como variables cuantitativas discretas. En lugar de un formato puramente binario, cada celda registra el número exacto de títulos conseguidos por el candidato en dicha categoría durante el período evaluado, permitiendo reflejar con precisión casos en los que se acumularon múltiples títulos en una misma temporada (como Ronaldo Nazario con dos títulos de selección en 1997, o conteos múltiples en otras categorías).
Las categorías fueron:
-Champions League (Copa de Europa).
-Título de selección (conteo de torneos oficiales con el combinado nacional).
-Liga nacional.
-Otros títulos relevantes (copas nacionales o internacionales adicionales).

Se conservó la variable de títulos totales como una suma agregada para facilitar agrupaciones y visualizaciones globales. Esta suma no pretende establecer que una Copa de Europa equivale a una liga o a un torneo de selecciones; solo registra el volumen total de éxitos colectivos acumulados en cada fila.

**Limitaciones**

La base contiene únicamente el top 3 de cada año, no a la totalidad de los nominados. Además, los títulos colectivos de las distintas ligas y competencias de la época no poseen exactamente el mismo peso competitivo. La base permite estudiar asociaciones estadísticas, pero no demostrar causalidad directa entre un título y un voto determinado.

**Preguntas que permite responder**
1.	¿Qué proporción de los ganadores del período ganó Champions?
2.	¿Cuántos segundos o terceros lugares tuvieron al menos un gran título colectivo?
3.	¿Qué excepciones existen entre éxito colectivo y posición final?
4.	¿Qué ocurre en los años con grandes torneos de selecciones?

**Replicabilidad**

Para repetir el proceso se parte del archivo original en Excel, se conserva una fila por edición y candidato, se normalizan los campos textuales, se codifican los títulos como conteos exactos de la temporada, se comprueban valores faltantes y se genera la variable derivada de títulos totales. Luego el archivo CSV resultante se puede cargar directamente en Pandas para generar tablas y visualizaciones.