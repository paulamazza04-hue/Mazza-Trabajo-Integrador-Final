# Mazza-Trabajo-Integrador-Final
Herramientas básicas para el Análisis de Datos

# 🏰 Introducción
El presente proyecto tiene como objetivo analizar la evolución del desempeño comercial de las películas producidas y distribuidas por Disney entre 1937 y 2016. Para ello, se utilizará información relacionada con la fecha de estreno, el género, la clasificación por edades y la recaudación de cada película, tanto en valores nominales como ajustados por inflación. El análisis permitirá identificar tendencias a lo largo del tiempo, determinar cuáles han sido los géneros más exitosos, evaluar la influencia de la clasificación MPAA sobre los ingresos obtenidos y reconocer las películas con mejor desempeño en taquilla. Asimismo, se buscará comprender cómo ha evolucionado la capacidad de generación de ingresos de Disney y cuáles son los factores que podrían estar asociados al éxito comercial de sus producciones.

# 🎬 Datos:
El análisis se realizó utilizando el dataset Disney Movies, obtenido de Kaggle. La información contiene datos históricos de películas de Disney, incluyendo año de lanzamiento, género, recaudación bruta e importe ajustado por inflación. A partir de estos datos se construyeron indicadores de desempeño (KPIs) para analizar la evolución de la recaudación por año y por género, así como la distribución y tendencias de las películas a lo largo del tiempo. Fuente: PrateekMaj21, Disney Movies Dataset, Kaggle. Disponible en: https://www.kaggle.com/datasets/prateekmaj21/disney-movies.


# 🪄 Exploración y limpieza de los datos
Durante la etapa de preparación de datos se realizó un análisis de calidad sobre el dataset. Se identificaron y eliminaron valores nulos para garantizar la consistencia de la información. Asimismo, se detectaron registros duplicados asociados a películas con el mismo nombre pero correspondientes a diferentes años de lanzamiento. Tras revisar estos casos, se concluyó que en muchos correspondían a secuelas, remakes o versiones live-action de producciones originales. Para diferenciarlas y evitar duplicidades en el análisis, se ajustó su identificación incorporando una numeración distintiva cuando fue necesario.

Adicionalmente, se eliminaron variables consideradas poco relevantes para los objetivos del estudio, como la clasificación de la MPAA, con el fin de simplificar el modelo de datos y mejorar la claridad del análisis. También se revisaron los valores mediante estadísticas descriptivas para detectar posibles inconsistencias, sin encontrarse valores negativos ni rangos fuera de lo esperado. Finalmente, el conjunto de datos depurado se almacenó en una nueva versión denominada data_set_limpio, preservando el archivo original para futuras consultas o validaciones.

<img width="562" height="232" alt="image" src="https://github.com/user-attachments/assets/7358c54d-ca4c-4f88-a810-fb26c3deb0cd" />

<img width="443" height="249" alt="image" src="https://github.com/user-attachments/assets/218e538e-534d-49c1-9b36-65c746b7c381" />


# 🎭 Preguntas de Análisis Resueltas por los Gráficos
A partir de las visualizaciones generadas, podemos plantearnos y responder las siguientes tres preguntas clave:

1. ¿Cuál es el género cinematográfico en el que Disney ha producido la mayor cantidad de películas históricamente?
2. ¿Cómo ha evolucionado los ingresos brutos totales de las películas de Disney a lo largo de las décadas?
3. ¿Existen éxitos que sobresalgan drásticamente en la historia reciente de la distribuidora?

## ⭐Predominancia de la Comedia y la Aventura:
El análisis de distribución reveló que el género de Comedia lidera la producción histórica de la compañía con un 31.4% de los títulos, seguido muy de cerca por Aventura y Drama. Esto demuestra la consistencia de Disney en enfocarse en contenidos familiares y de entretenimiento masivo.

## 🎥 Evolución y Crecimiento Financiero:
Los ingresos brutos totales muestran una tendencia de crecimiento exponencial en las últimas décadas. Aunque históricamente producciones clásicas sentaron las bases de la marca, la taquilla moderna (especialmente a partir de los años 90 y consolidadas en los 2010 con franquicias y adquisiciones como Marvel o Star Wars) representa la era de mayores ingresos absolutos en la historia de la compañía.

## ⭐🚀Identificación de Éxitos Excepcionales: 
Los gráficos interactivos nos permitieron aislar e identificar de manera clara aquellos títulos que redefinieron los récords en fechas recientes así como Star Wars y Marvel, facilitando el análisis visual e interactivo de los datos.

# ⚔️✨Conclusión del Análisis de Importes e Inflación a través de los Años
Al contrastar los importes de taquilla bruta frente a los ingresos ajustados por inflación de las películas de Disney a lo largo del tiempo, podemos extraer las siguientes conclusiones clave:

## 🎭 La distorsión del valor del dinero: 
Si analizamos únicamente el Importe Bruto, parecería que las películas más exitosas de Disney pertenecen exclusivamente a la época moderna (años 2000 en adelante). Sin embargo, al aplicar el Ajuste por Inflación, descubrimos que los verdaderos titanes financieros de la compañía fueron estrenados en su primera etapa, destacando Snow White and the Seven Dwarfs (1937) y Pinocchio (1940), cuyos ingresos equivalen a más de 2 mil millones de dólares actuales cada una.
## ✨📈Cambio en el modelo de negocio: 
En las primeras décadas, Disney estrenaba menos películas, pero cada una de ellas lograba un impacto masivo y duradero con reestrenos constantes en cines. En las décadas de los 90 y 2010, observamos una mayor frecuencia de lanzamientos con recaudaciones brutas altísimas en su estreno inicial, pero que en términos de valor adquisitivo real promedio no logran superar de manera individual a los clásicos históricos.
## 🏰💰 El valor de la perspectiva histórica:
Este análisis demuestra que evaluar el éxito financiero de un catálogo histórico sin ajustar los datos por inflación genera una conclusión sesgada. El ajuste nos permite valorar la verdadera magnitud del éxito cultural y comercial de las obras fundacionales de Disney en su momento de estreno.

## KPI en Power
KPI	Descripción	Objetivo
📈 Importe Ajustado Total:	Suma de la recaudación ajustada por inflación.	Comparar ingresos reales a lo largo del tiempo.
📅 Importe Bruto por Año:	Recaudación bruta agrupada por año de estreno.	Analizar la evolución anual de ingresos.
🏰 Importe Ajustado por Año	Recaudación ajustada agrupada por año.	Identificar los años más exitosos considerando la inflación.
📊 Participación por Género (%)	Porcentaje que representa cada género sobre el total recaudado.	Medir el peso relativo de cada género.
📅🎭 Importe por Género y Año	Recaudación segmentada por género y año.	Analizar tendencias de cada género en el tiempo.

# Autora 
Ana Paula Mazza// Contadora Publica
