 ## Proyecto de Análisis de Siniestros Viales en la Ciudad de Buenos Aires ##


 ####  Análisis de datos para la reducción de víctimas fatales ####


 #### Presentacion de la problematica : ####

 Ciudades densamente pobladas como Buenos Aires enfrentan un serio problema de seguridad vial debido al elevado número de accidentes de tránsito. Estos eventos no solo ponen en riesgo la vida de los ciudadanos, sino que también generan un impacto negativo en la infraestructura y los servicios de emergencia.


 #### Tarea a desarrollar: contexto y datos : ####

 El presente estudio se centra en el análisis cuantitativo de datos relativos a siniestros viales con desenlace fatal ocurridos en la Ciudad Autónoma de Buenos Aires entre los años 2016 y 2021. A través del procesamiento de un conjunto de datos estructurados en formato Excel (XLSX), compuesto por las hojas 'Hechos' y 'Víctimas', y enriquecido con un diccionario de datos, se busca generar conocimiento que permita a los tomadores de decisiones implementar estrategias para reducir la siniestralidad vial. La investigación se sustenta en un conjunto de datos en bruto, los cuales han sido transformados y procesados para su análisis. 


#### Labor Realizado : ####

#### Extraccion, Transformacion y Carga de datos : ####

*Tratamiento y Preparación de los Datos : 

Para la presente investigación, se empleó un conjunto de herramientas informáticas con el fin de recopilar, limpiar y transformar los datos, previo a su análisis. Específicamente, se utilizaron las librerías de Python pandas y, en casos particulares donde se requirió una mayor flexibilidad en la conexión a fuentes de datos, Power Query dentro de la plataforma de Business Intelligence Power BI.

*Extracción de Datos : 

Los datos primarios fueron obtenidos a partir de dos conjuntos de datos (datasets) almacenados en formato Excel. Estos datasets constituyeron la base empírica sobre la cual se construyó el análisis.

*Transformación de Datos : 

Una vez extraídos los datos, se llevó a cabo un proceso exhaustivo de limpieza y transformación con el objetivo de garantizar la calidad y coherencia de la información. Las principales operaciones realizadas fueron:

- Eliminación de registros incompletos : Se procedió a eliminar aquellos registros que contenían valores nulos en todas sus variables, a partir de la fila 696.

- Depuración de duplicados : Se identificaron y eliminaron los registros duplicados, asegurando así la unicidad de cada observación.

- Imputación de valores faltantes : Se aplicaron técnicas de imputación para gestionar los valores faltantes, seleccionando la metodología más adecuada en función de la naturaleza de las variables y el contexto del análisis.

- Conversión de tipos de datos : Se verificó y ajustó el tipo de dato de cada variable, garantizando su compatibilidad con las operaciones analíticas posteriores.

- Ingeniería de características : Se crearon nuevas variables a partir de las existentes, con el fin de enriquecer el análisis y capturar relaciones más complejas entre las variables.

*Carga de Datos :

Los datos transformados fueron cargados en la herramienta de Business Intelligence Power BI. Esta plataforma permitió visualizar y explorar los datos de manera interactiva, facilitando así la generación de informes y la toma de decisiones basadas en evidencia.


#### Analisis Exploratorio de Datos : ####

A través de un análisis exploratorio de datos (EDA), se buscó comprender las tendencias y factores que influyen en la ocurrencia de accidentes de tránsito con víctimas fatales. Para este propósito, se utilizaron las bibliotecas pandas, numpy, seaborn y warnings, las cuales facilitaron la manipulación y visualización de los datos.

#### Power BI Dashboard : ####

Con el fin de profundizar en el conocimiento de la problemática de la siniestralidad vial en la Ciudad Autónoma de Buenos Aires, se diseñó un tablero de control interactivo ('Análisis_accidentes_viales_CABA.pbix'). Esta herramienta posibilita:

- Caracterizar el perfil de las víctimas fatales y los contextos en los que ocurren los siniestros.

- Detectar tendencias y áreas críticas en materia de seguridad vial.

- Informar a las autoridades competentes para la toma de decisiones basadas en evidencia y la implementación de estrategias de prevención.

- Facilitar la evaluación del impacto de las medidas implementadas y el seguimiento de los objetivos en materia de seguridad vial.

#### Bibliotecas Utilizadas : ####

- pandas
- numpy
- seaborn
- warnings

#### Efectos Deseados : ####

La presente investigación tiene como objetivo primordial suministrar datos relevantes a las autoridades municipales para propiciar en la disminución de fatalidades por siniestros viales en la Ciudad de Buenos Aires, con el fin último de fomentar un entorno vial más seguro.

#### Autora : ###

Este proyecto fue realizado por Nadia Scolese .

