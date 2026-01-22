# Shark Attack Analysis

## Description 
Este proyecto consiste en el análisis de un dataset histórico sobre ataques de tiburones con el objetivo de identificar patrones relevantes, como:
* Actividades con mayor número de ataques, siendo o no provocado 
* Relación entre ataques fatales y su nivel de provocación en el ataque
* Distribución temporal de los ataques en el año

## Tabla de Contenidos
- [Instalación](#instalación)
- [Uso](#uso)
- [Dataset](#dataset)
- [Preguntas de Investigación](#preguntas-de-investigación)
- [Análisis](#análisis)
- [Resultados](#resultados)
- [Contribución](#contribución)

## Instalación
1. Clonar el repositorio:
   git clone https://github.com/MonicaFernandezM/semana-ataque-tiburones.git

2. Abrir el proyecto en Jupyter Notebook.

3. Ejecutar el notebook principal para reproducir el análisis.

No es necesario instalar dependencias adicionales si ya se cuenta con un etorno estándar de ánalisis de datos en Python. 

## Uso 
* Abrir el notebook del proyecto.
* Ejecutar las celdas en orden.
* Explorar los resultados.

El análisis está organizado por secciones para facilitar la comprensión del flujo de trabajo.

## Dataset

Pulsa en [The International Shark Attack File](https://www.sharkattackfile.net/incidentlog.htm)para descargarlo en tu equipo.

El dataset utilizado contiene información sobre ataques de tiburones a nivel mundial. Incluye variables como:
* Fecha del ataque
* Actividad realizada
* Tipo de Ataque
* Edad de la persona
* Tipo de ataque (Provoked, Unprovoked, Unknown)
* Genero de la persona
* Resultado fatal (Y/N)
* Ubicación, entre otras

El dataset ha sido previamente limpiado para eliminar valores inconsistentes y facilitar el análisis

## Preguntas de Investigación
- ¿Mueren más hombres que mujeres en los ataques de tiburones?
- ¿Cuál es la relación entre ataques provocados y ataques fatales?
- ¿Qué actividades están asociadas a un mayor número de muertes y fueron estos ataques provocados o no provocados?
- ¿En qué país se ha registrado el mayor número de ataques de tiburones?
- ¿En qué época del año se producen más ataques de tiburones?

## Análisis realizado
El proyecto incluye:
* Limpieza de datos (manejo de valores nulos y fechas inconsistentes)
* Extracción y normalización de variables
* Análisis de ataques fatales por actividad
* Comparación entre ataques provocados o no
* Agrupaciones y conteos para detectar patrones relevantes

## Resultados 

- Diferencias de mortalidad por sexo
Nuestro resultados indican que, del total de 6.480 registros, la mayoría de las muertes corresponden a hombres. En concreto, se registraron 5.670 fallecimientos de hombres, lo que representa aproximadamente el 87,5% del total, frente a 810 mujeres, que suponen el 12,5%

- Años con mayor número de muertes
El análisis temporal muestra que el año 2015 fue aquel en el que se registró un mayor número de muertos, con 130 fallecimientos sobre un total e 6.371 registros.
En segunda posición se encuentra 2017, con solo dos muertes menos, y en tercer lugar 2016, con 122 registros. Estos datos indican un pico de mortalidad concentrado en ese período.

- Relación entre ataques provocados y mortalidad
En cuanto al tipo de ataque:
* 21 personas fallecieron tras provocar el ataque, mientras que 613 personas sobrevivieron a ataques provocados.
* Por otro lado, 1.266 personas murieron en ataques no provocados, y 3.872 personas fueron atacadas sin provocar el ataque y sobrevivieron.
* Además, existen 50 casos en los que no se conoce si el ataque fue provocado o no, y 586 ataques se produjeron por otras causas (como desastres naturales o situaciones de supervivencia).
Estos resultados indican que la mayoría de las muertes se producen en ataque s no provocados. 

- Países con mayor número de ataques:
El análisis geográfico revela que los cinco países con mayor número de ataques de tiburón son:
1. Estados Unidos
2. Australia
3. Sudáfrica
4. Nueva Zelanda
5. Papúa Nueva Guinea
Estos países concentran la mayor parte de los incidentes registrados en el dataset.

- Época del año con mayor número de ataques
El análsis por trimestres muestra que la mayor concentración de ataques de tiburón se produce en el tercer trimestre del año (julio, agosto y septiembre), con un total de 1.578 registros.

En segundo lugar se encuentra el segundo trimestre (abril, mayo y junio) con 1.268 ataques, seguido del cuarto trimestre (octubre, noviembre y diciembre) con 1.231 registros.

Por último, el trimestre con menor número de ataques es el primer trimestre (enero, febrero, marzo) con 1.182 casos. 

Estos resultados sugieren que los ataques de tiburón son más frecuentes durante los meses de verano, lo que podría estar relacionado con mayor presencia humana en el mar y aumento de actividades acuáticas en esta época del año.

## Contribución 

Las contribuciones son bienvenidas.
Si deseas mejorar el análisis o añadir visualizaciones:
1. Haz un fork del repositorio
2. Crea una nueva rama 
3. Realiza tus cambios
4. Abre un Pull Request 