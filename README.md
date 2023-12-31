<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# POYECTO INDIVIDUAL DATA ANALYST 
by Ricardo Moreno
### PROYECTO INDIVIDUAL **`PI02: PI DATA ANALYTICS`** (DATA SCIENCE Part-Time-01 SOY HENRY)

¡Bienvenidos al último proyecto individual de la etapa de labs! En esta ocasión, deberán hacer un trabajo situándose en el rol de un Data Analyst.

Nuestro Cliente, una empresa prestadora de servicios de telecomunicaciones me encarga la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Considere que la principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.



# INFORME


En respuesta a la solicitud de nuestro cliente analizamos los datos obtenidos de **https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/** 

Esta API nos proporciona 16 Datasets, de acuerdo con la solicitud del cliente solo analizaremos el servicio de Internet a nivel nacional, por esta razón solo usaremos los siguientes archivos:

5. **historico_velocidad_internet_por_Prov.csv**

9. **Internet_Accesos-por-tecnologia_por_Prov.csv**

11. **Internet_Accesos-por-velocidad_por_Prov.csv**

13. **Internet_Ingresos.csv**

14. **Listadodelocalidadesconconectividadainternet.csv**

15. **Penetracion_fijo_por_cada_100_Hogares.csv**

17. **Ingresos_trimestrales_telefonía móvil.csv**


Estos archivos fueron analizados con la librería YDATA-PROFILING, esta libreria nos proporciona un analisís EDA simple, mostrándonos procentajes en blanco o con valor cero, analiza valores únicos, analisís de rango y de fecha y extensíon de los estrings maxímos y minimos.info: ***https://github.com/ydataai/ydata-profiling***

Para la presentación del informe usaremos **Power BI**, aunque los datos estan bastante limpios realizaremos algunas transformaciones con ayuda de Power Query de ser necesarias, sin embargo el analisís preliminar nos dice que los achivos no necesitan ninguna transformación.

## Presentación

Ente Nacional de Comunicaciones, ENACOM, es una agencia gubernamental de Argentina responsable de regular y supervisar el mercado de las comunicaciones en La Republica de Argentina. Su objetivo principal es conducir el proceso de convergencia tecnológica y crear condiciones estables de mercado para garantizar el acceso de todos los argentinos a los servicios de internet, telefonía fija y móvil, radio, postales y televisión

Entre las principales funciones de ENACOM se encuentran la regulación y el control del uso del espectro radioeléctrico, la asignación de licencias de servicios de telecomunicaciones, la promoción de la competencia en el mercado de las comunicaciones, la protección de los derechos de los usuarios, entre otras. Su objetivo es garantizar el acceso universal, equitativo y asequible a los servicios de comunicaciones en Argentina.

### Objetivos
Como objetivos definidos tenemos mostrar la evolución del servicio de internet fijo desde el 2014 hasta el 2022,mediante el cruce de Datos y la relacion de Tablas, mostraemos: La suma de ingresos por año y trimestre, observar el ingreso por servicio de telefonía celular para evaluar como complemento de negocio, porcentaje de accesos a internet por cada 100 hogares, Comparamos las velocidades de bajada en nuestro periodo de tiempo, si como los acceso por año y tecnologia.


Mediremos también la variación del servicio por tecnologia de internet, Velocidad de internet por provincia, distribución del acceso a internet según la Provincia, tipo de tecnología más usada, en consecuencia la de mayor crecimiento para cubrir la demanda, acceso a internet por provincia y Tecnologia,  la velocidad media por provincia, deacuerdo a la ubicacion geografica por provincia, móstar las localidades que tienen y no servicio de internet como oportunidad de aumento de la cobertura.

### Concluciones
 En definitiva, este conjunto de información proveerá una herramienta clara y acertada pera evaluar los requerimientos y beneficios de prestar en la República Argentina el servicio de internet enfocado al cliente final.Se puede aprovechar el aumento en la demanda del servicio de internet así con el de la de telefonía móvil y por consiguiente el servicio de internet móvil, unido esto ala cobertura y velocidad general del país, pueden vislumbrarse oportunidades de negocio hacia los lados de las provincias alejadas de la capital.

La información mostrada es definitiva para la toma de decisiones para más profundidad se buscaria dar más volumen al informe y detallar algunos puntos que causen más información.

Gracias por la atención prestada.




##### QUIERO AGRADECER A DIOS Y BENDECIR A TODOS LOS COMPAÑEROS, AMIGOS Y FAMILIARES QUE DE UNA U OTRA FORMA ME AYUDARON A DESARROLLAR ESTE PROYECTO! 
