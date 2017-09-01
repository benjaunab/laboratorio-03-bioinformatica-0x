# Laboratorio 03 - Ensamblaje de genomas y predicción de genes

## Parte 1: El artículo genoma

### ¿Cuántos genomas han sido depositados en GOLD? ¿Son los mismos de GENBANK?

_R_: Entre projectos completados e incompletados da una suma de 64754 projectos totales (Complete Projects 11.598 y Incomplete Projects 53.156, respectivamente). GENBANK posee 80.576 genomas.

### ¿Cuál es la distribución de procariontes y eucariontes secuenciados?

_R_: 80.576 procariontes y 18.241 eucariontes.

### ¿Qué es el N50, L50, NG50?

_R_: El N50 es un valor estadistico que evalua la calidad de un ensamble, indica el tamaño minimo que debe tener un contig que cubre la mitad de la longitud total de los contig. El L50 es el numero de contig que se necesitaron para llegar a la mitad de todos los contig. El NG50 es lo mismo que el N50 pero se compara con el largo total del genoma.  

### ¿Cuál es el propósito de calcular estas estadísticas?

_R_: Este conjunto de estadiscticas ayudan a tener una referencia a las longitudes dentro de un contig y de esta forma ayudar en el ensamblaje del genoma.

### ¿Cuál es el genoma que escogiste? Adjunta la referencia.

_R_: EL genoma Y22-3 [Referencia](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4889671/)
 

### ¿Cuál es el N50 del genoma que escogiste? ¿Y el NG50?

_R_: [Tabla](https://drive.google.com/file/d/0B0rzqm380_roYm1fNmdFdmdUTzA/view?usp=sharing)

### ¿Qué tipo de tecnología se uso para secuenciar el genoma que escogiste?

_R_: Usan  Illumina HiSeq y PacBio.  

### ¿Qué organismo escogiste, cuántos cromosomas tiene tu organismo y cuál es su tamaño?

_R_: Saccharomyces cerevisiae, posee 16 cromosomas y tiene un largo medio de 12.1246 (Mb)

## Parte 2: Predicción de genes

### ¿Cuántos ORF o genes encontró ORFfinder?

_R_: ORFfinder encontro 7 ORC.

### 	¿Cuántos ORF o genes encontró Glimmer?

_R_: Glimmer encontro 10 ORC.

### 	¿Alguno de los genes predichos por estas herramientas coinciden?

_R_: coinciden con un gen que posee 441 nucleotidos.

### ¿En qué hebra están codificados?

_R_: El gen que coincide en ambas herremientas, ORFfinder muestra que esta en la hebra negativa, pero en GLIMMER aparece que es positiva.

### 	¿Qué tipo de programa es GLIMMER? ¿Ab initio o por homología?

_R_: Glimmer es un sistema para encontrar genes en el ADN microbiano, especialmente los genomas de bacterias, arqueas y virus. Utiliza modelos de Markov interpolados para identificar las regiones de codificación y distinguirlos del ADN no codificante, osea, funciona por homologias.

### Describe los resultados encontrados con respecto a los genes que encontraste con GLIMMER y ORFfinder usando el BLAST.

_R_: Con respecto a los genes entregados por ORFfinder, al usar el BLAST se encontraron 2 genes que no encontro semejanza significativ con la base de datos. Tambien se encontraron genes que poseían un gran puntaje de aliniamiento como bajos puntajes de alineamiento. En el caso de GLIMMER los 10 genes que se analizaron tuvieron una semejanza en la base de datos y el puntaje de alineamiento, en cada gen, fue bastante alta en comparacion a los resultados entregados por ORFfinder.
