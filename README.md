# Semana2_Shark_Attacks
En este proyecto limpiamos un conjunto de datos desordenado (Shark Attacks) mediante técnicas de data wrangling.

Cosas a cambiar de types: Age a int, date a ?, Year a int? (habría que mantener nulos y usar Int64? df["Year"] = df["Year"].astype("Int64"))
Tenemos datos vacíos, países repetidos con diferentes nombres, faltan años, fechas etc

hipótesis: 
1. Tiene relación el tipo de actividad con recibir más ataques de tiburones?
2. Ciertas lesiones aumentan la probabilidad de que el ataque sea fatal?
3. Temporada del año
4. El número de ataques ha aumentado o disminuido con los años?

Título del proyecto → Shark Attack Analysis: Data Cleaning & Insights
Objetivo del proyecto → Transformar un dataset histórico de ataques de tiburón en una base de datos limpia y estructurada para identificar patrones de riesgo, con el fin de informar a tomar decisiones de seguridad y prevención.
Contexto del negocio → Este análisis podría ser usado por organizaciones de turismo y seguridad costera que necesitan comprender qué actividades presentan mayor riesgo de ataques de tiburón. La meta es priorizar medidas preventivas y recursos de seguridad, optimizando la protección de los visitantes y residentes.
Dataset → Global Shark Attack File (GSAF) https://www.sharkattackfile.net/spreadsheets/GSAF5.xls
Registros originales: 
Variables clave: 
- country: país del ataque
- activity: actividad de la víctima
- injury: descripción de la lesión
- fatal: resultado del ataque (y/n/unknown)
Notas sobre calidad del dato: Varias columnas con valores nulos, inconsistencia en categorías
Preguntas clave →
- ¿Existen tipos de lesión (injury) asociados a mayor probabilidad de que el ataque sea fatal?
- ¿Influye la actividad (activity) en la fatalidad de los ataques en los países con más incidentes?
Proceso de análisis → Describe brevemente: EDA, limpieza, KPIs calculados, métricas clave usadas, metodología aplicada
(cohortes, RFM, funnels, etc.)
Resultados / Insights → Los hallazgos más importantes, claros y accionables.
Recomendaciones de negocio → Tu interpretación profesional:qué decisión tomar, qué experimentos lanzar, qué
optimizar, qué priorizar.
Limitaciones → Demuestra pensamiento crítico.
Próximos pasos → Qué extenderías si tuvieras más datos o más tiempo.
Cómo replicar el proyecto → Enlace al notebook, queries SQL o dashboard