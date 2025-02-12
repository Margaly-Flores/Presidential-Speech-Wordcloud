<h1 align=center><font size = 5> Análisis del Mensaje a la Nación de la Presidenta del Perú 🏛️</font></h1>

### Introdución
En el contexto político, Dina Boluarte, actual presidenta del Perú, ha alcanzado un nivel de desaprobación sin precedentes. Según una encuesta de Datum para El Comercio realizada en junio de 2024, solo el 5% de la población la respalda, marcando la cifra más baja registrada por un jefe de Estado en el Perú desde 1980. Esta situación refleja un clima de profunda crisis política y social, en el que la mandataria enfrenta uno de los desafíos más grandes en la historia reciente del país.

Ante este panorama, he tomado la iniciativa de analizar dos de sus discursos presidenciales con el fin de identificar los temas centrales, las palabras más utilizadas y posibles patrones en su retórica. A través de técnicas de procesamiento de lenguaje natural (NLP), este análisis busca ofrecer una perspectiva objetiva sobre el enfoque discursivo de la presidenta en un contexto de creciente descontento ciudadano.

![](/images/palace.jpg)

### Descripción del Proyecto
----
En este proyecto utilizaré PyMuPDF, una biblioteca de Python que facilita la manipulación de documentos PDF, formato en el que se encuentran los discursos presidenciales. Esto me permitirá extraer y analizar el texto, obteniendo una visión clara de las palabras más comunes en dos discursos de la presidenta del Perú publicados en la página oficial del gobierno.

Después de extraer el texto con Fitz y realizar su limpieza, emplearemos el paquete word_cloud para transformar la información en una nube de palabras, resaltando los términos más utilizados. Además, utilizaré Matplotlib para visualizar y comparar las 10 palabras más frecuentes en cada discurso, permitiendo analizar las diferencias entre ambos, dado que corresponden a intervenciones consecutivas.

Finalmente, presentaré los resultados mediante gráficos de barras horizontales generados con Matplotlib.

### Datos
----
Los datos de este proyecto fueron extraídos del sitio oficial de transcripción de discursos del Gobierno del Perú [(gob.pe/mensajepresidencial)](gob.pe/mensajepresidencial) y posteriormente limpiados para eliminar elementos irrelevantes, como enumeraciones, anotaciones y formatos decorativos que podrían afectar el análisis.

Para el estudio, se utilizaron las transcripciones de los discursos del **29 de enero de 2023** y el **28 de julio de 2023**.


### Resultados
----
**Discurso del 29 de enero de 2023, 10 palabras top:**
- República
- total
- propuesta
- responsabilidad
- adelanto
- Constitución
- 2023
- reforma
- elecciones
- Congreso

**Discurso del 28 de julio de 2023, 10 palabras top:**
- desarrollo
- nivel
- proyectos
- salud
- Perú
- Nacional
- Ministerio
- país
- inversión
- Gobierno




### Referencias
----
https://www.gob.pe/mensajepresidencial

https://elcomercio.pe/politica/gobierno/dina-boluarte-aprobacion-de-la-presidenta-cae-a-5-en-junio-segun-encuesta-datum-internacional-se-marca-un-record-historico-negativo-desde-los-1980-fernando-belaunde-alan-garcia-alberto-fujimori-noticia/

https://www.infobae.com/peru/2024/06/09/dina-boluarte-se-vuelve-la-presidenta-mas-impopular-del-siglo-solo-el-5-de-peruanos-la-apoya/

https://github.com/PhinanceScientist/AMLO_Wordcloud/tree/master
