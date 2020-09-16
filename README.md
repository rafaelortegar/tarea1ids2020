# Data Science Project Scoping Worksheet

**Profesor:** Liliana Millán Núñez

**Integrantes del equipo**

| # | Alumno                           | Clave única |
|---|-----------------------------------|-------------|
| 1 | Angel Rafael Ortega Ramírez | 123972      |
| 2 | Leo         | CU      |
| 3 | Toño         | CU      |
| 4 | Mario         | CU      |
| 5 | Carlos Román         | CU      |
| 6 | Arthur         | 197814      |
| 7 | Carlos Bautista         | CU      |


1. **Nombre del proyecto:** Envenenamiento por plomo

2. **Nombre de la organización:** Departamento de Salud Pública de Chicago

3. **Descripción del problema:**

    3.1. ¿Cuál es el problema al que se enfrenta?
    Casos de envenenamiento por plomo en niños en la ciudad de Chicago.

    3.2. ¿Quién/qué es afectado por este problema?
    Niños menores de 6 años.

    3.3. ¿Cuántas personas/organizaciones/lugares/etc. y qué tanto son afectados?
    De acuerdo con los datos demográficos de Chicago, existen alrededor de 2,693,976 personas, de las cuales 6.5% corresponden a niños con una edad debajo de 5 años, de los cuales se tuvieron 1,000 casos de envenenamiento reportados en 2014.

    3.4. ¿Por qué resolver este problema es una prioridad para la organización?
En materia de salud y prevención, la población infantil resulta especialmente vulnerable, por lo que la prevención y conservación de la vida es una prioridad. Adicionalmente, la detección oportuna de exposición a plomo permitirá disminuir el riesgo de efectos a largo plazo que repercutan en la calidad de vida de los infantes.

4. Objetivos: Cuáles son las metas de negocio/política que serán logradas al resolver este problema y qué restricciones se tiene? (en orden de prioridad). 


| #|Objetivo       | Limitaciones  |
|--|---------------|---------------|
|1 |Reducir el número de casos de envenenamiento por plomo en niños.|No es cuantificable a corto plazo y no lleva a una acción concreta.|
|2 |Mejorar la precisión de las inspecciones  e intervenciones por el departamento de salud en lugares de riesgo a exposición.|Número limitado de inspectores con los que cuenta el departamento de salud.|
|3 |Incrementar la atención médica oportuna a niños con exposición a plomo.|Número restringido de especialistas de la salud con los que se cuenta.|


5. Acciones

| |Acción 1|Acción 2|Acción 3|Acción 4|
|-|--------|--------|--------|--------|
|Acción:|Efectuar las inspecciones|Brindar servicio de minimización de elementos riesgosos|Evaluar el efecto o daño producido por la exposición al plomo en el niño|Canalizar con especialista en salud para revertir o detener daños|
|¿Quién está ejecutando la acción?|Inspectores|Inspectores|Equipo médico|Equipo médico|
|¿Sobre quién o qué se está ejecutando la acción?|Inmuebles enlistados|Inmuebles detectados con riesgo de plomo|Niños expuestos a plomo|Niños con daños o alta exposición a riesgo|
|¿Con qué frecuencia hay que tomar la acción?|Diaria|Cada vez que haya sido detectado un niño con exposición a plomo en el inmueble|Cada vez que haya sido detectado un niño con exposición a plomo en el inmueble|Cada vez que haya sido detectado un niño con exposición a plomo|
|¿Qué canales se usan o se pueden usar para tomar esta acción?|Censos e inventarios de inmuebles|Resultados de años anteriores|Listado de inmuebles detectados como riesgosos|Servicio de atención médica subcontratado|Hospitales locales de la comunidad|Más información útil sobre la acción.|

6. Datos
    A. ¿Qué fuentes de datos internas tenemos internamente?

|        |Fuente 1|Fuente 2|
|--------|--------|--------|
|Nombre  |Pruebas de sangre por envenenamiento por plomo|Registros de inspección de plomo en inmuebles|
|¿Qué es lo que contiene?|Concentración de plomo en la sangre de los niños|El nivel de riesgo en el inmueble por exposición a plomo y si existe o no presencia de niños|
|¿Cuál es el nivel de granularidad?|Por individuo al que se le aplica la prueba|Por hogar|
|¿Con qué frecuencia es recolectado/ actualizado después de ser capturado? |Cada vez que se detecta que un niño ha sido detectado en riesgo por exposición al plomo|Cada vez que se hace una nueva inspección en inmueble|
|Tiene identificadores confiables y únicos que pueden ser conectados a otras fuentes de datos?|Sí|Sí|
|¿Quién es el propietario interno de los datos?|Departamento de Salud Pública de Chicago|Departamento de Salud Pública de Chicago|
|¿Cómo se almacena?|Dispositivo electrónico (con datos descargables en csv)|Dispositivo electrónico (con datos descargables en csv)|
|Comentarios adicionales|      |      |

   B. ¿Qué datos se pueden obtener de fuentes externas, privadas o públicas?

|   |Fuente 1|Fuente 2|Fuente 3|Fuente 4|Fuente 5|
|---|--------|--------|--------|--------|--------|
|Nombre|Censo|Shapefile de la ciudad|Registros catastrales|Censo económico|Registro de casos de envenenamiento por plomo|
|¿Qué es lo que contiene?|Distribución geográfica de la población por edad|Características geoespaciales de los inmuebles (tamaño, ubicación, densidad, etc)|Registro de construcciones y remodelaciones de inmuebles|Características económicas de la población|Registro de envenenamientos por plomo en niños a nivel estatal|
|¿Cuál es el nivel de granularidad?|Manzana|Nivel inmueble|Nivel inmueble|Manzana|Condado|
|¿Con qué frecuencia es recolectado/actualizado?|10 años|10 años|Mensual|10 años|Mensual|
|Tiene identificadores confiables y únicos que pueden ser conectados a otras fuentes de datos?|Sí|Sí|Sí|Sí|Sí|
|¿Quién es el propietario interno de los datos?|Gobierno|Gobierno|Gobierno de Chicago|Gobierno|Gobierno (CDC)|
|¿Cómo se almacena?|csv|shapefile|csv|shapefile|geojson|csv|csv|
|Comentarios adicionales|  |  |incertidumbre si la actualización de los datos y la disponibilidad son simultáneas|   |Serán útiles para tener un punto de comparación con el número de pruebas y envenenamientos en el Estado|


   C.En un mundo ideal, ¿qué datos adicionales te gustaría tener/recolectar que serían relevantes para el problema?
   Encuestas realizadas en escuelas a padres de familia de niños menores de 6 años: Se desea conocer las características de los hogares, las condiciones de trabajo y grado escolar de los padres de familia.


7. Análisis

|  |Análisis 1:|Análisis 2:|
|--|-----------|-----------|
|Tipo de Análisis|Clasificación|Scoring|
|Propósito del análisis|Dividir los inmuebles en categorías de riesgo y sin riesgo.|Otorgar una calificación a los inmuebles categorizados como en riesgo para priorizar orden de inspecciones|
|¿Qué acción será informada por este análisis?|Los lugares a los que se realizará la inspección|Los lugares a los que se realizará la inspección|
|¿Cómo se validará el análisis utilizando datos existentes? ¿Qué metodología y métricas se utilizarán?|Empleado los datos históricos sobre envenenamiento por plomo en niños evaluar la precisión de las clasificaciones efectuadas.|Empleado los datos históricos sobre envenenamiento por plomo en niños evaluar la precisión de las clasificaciones efectuadas.|

8. Consideraciones éticas

|Privacidad ¿Se trabaja con datos personales y/o sensibles que pueden ser identificados identificables? Mencionarlos|La presencia de niños en una casa específica, La situación de salud de un individuo,Dirección del domicilio,Bienes materiales dentro de una vivienda,Identidad de los habitantes de la casa|
|------|--------|
|Transparencia ¿Qué stakeholders deben estar informados sobre qué partes del proyecto?|Director del departamento de salud, sobre los planes de implementación de médicos.    Director del departamento de inspección, sobre la forma en la que se utilizarán los inspectores.     Departamento de T.I. o proveedores de servicios tecnológicos, sobre utilización de tablets y desarrollo de una plataforma para la implementación de las inspecciones.    Autoridades policiacas locales, sobre el hecho que habrá personas realizando inspecciones en ciertos días en ciertos lugares.    Dirección de educación pública, sobre que se planean realizar pruebas de sangre en escuelas.|
|Discriminación/Equidad ¿Existen grupos específicos para quienes se busca asegurar equidad en los resultados?|Habitantes de zonas marginadas y conglomerados poblacionales con poca población. Personas de minorías raciales. Familias monoparentales.|
|Licencia Social Sí toda la población del país se enterara del proyecto, ¿estarían de acuerdo con él? ¿Por qué?|En general, la población estaría de acuerdo en minimizar factores de riesgo en la salud de los niños. Aunque pueden existir personas que se opongan a que un extraño entre a su domicilio y a la toma de muestras de sangre.|
|Responsabilidad ¿Quiénes son las personas responsables por todo lo establecido anteriormente?|Departamento de salud pública de Chicago, Consultores de ciencia de datos, Proveedores de infraestructura tecnológica y de servicios de almacenamiento y recolección de datos, Inspectores empleados|
|Otras consideraciones como consentimiento, leyes, etc.|Entrar a escuelas e inmuebles para realizar mediciones de factores de riesgo, así como realizar tomas de sangre.|

9. ¿Qué prueba de campo o prueba aleatorizada controlada puedes diseñar para validar el proyecto en el campo?

Prueba por permutación. Para determinar si a los inmuebles donde se encontró riesgo por plomo, en las pruebas de sangre se detectó mayor plomo.
Visitas aleatorias a ubicaciones categorizadas como sin riesgo para verificar que en efecto no existen riesgos de exposición de niños a plomo.


10. ¿Quiénes son las organizaciones externas y los departamentos internos que deben estar involucrados?

|Organización/Departamento|Descripción del involucramiento deseado|Nombre / Rol de Contraparte|
|-------------------------|---------------------------------------|---------------------------|
|Departamento de salud pública de Chicago|En todos los pasos del proyecto|Tomadores de decisiones|
|Gobierno de Illinois|Conocer los objetivos del proyecto|Facilitador de información|
|Departamento de finanzas|Emisión de facturas|Proveedor de los recursos económicos|
|Proveedor de infraestructura, servicios tecnológicos y almacenamiento de datos|Implementación de las herramientas requeridas|Proveedor de servicios e infraestructura|



1	Leo
2	Leo
3	Leo	
4	Leo
5	Toño 
6 	Mario
6 	Carlos Román 
6 	Carlos Román
7	Arthur
8	F Carlos Bautista
9	G Rafa Ortega
10	G Rafa Ortega
