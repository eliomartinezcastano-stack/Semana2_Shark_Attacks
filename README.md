# Semana2_Shark_Attacks

🎯 Objetivo del proyecto
Transformar el dataset histórico Global Shark Attack File (GSAF) en una base de datos limpia y estructurada. El propósito es identificar patrones de riesgo y factores que influyen en la fatalidad de los ataques para informar decisiones de seguridad costera y prevención.

🛠️ Proceso de Análisis (Data Wrangling)
El proyecto se centró en la limpieza profunda de un dataset con 7,065 registros y 23 variables iniciales:

Limpieza de Texto: Estandarización de columnas (country, activity, injury, fatal) a minúsculas y eliminación de caracteres especiales.

Filtrado Significativo: Se redujo el análisis a los 3 países con mayor volumen de datos para asegurar relevancia estadística: USA, Australia y Sudáfrica.

Categorización: Se agruparon más de 1,600 actividades en 6 categorías principales (Surfing/Boarding, Swimming, Fishing, Diving, Boating, Other) mediante expresiones regulares.

Tratamiento de Nulos: Identificación de columnas críticas con alta ausencia de datos (como Time con un 50% de nulos) para decidir su exclusión o tratamiento.

🚀 hipótesis: 

1. Hipótesis 1- ¿Existen tipos de injury(lesion) asociados a mayor probabilidad de que el ataque sea fatal?

2. Hipótesis 2- ¿Influye el tipo de actividad con respecto a la fatalidad en los países con más ataques?

📈 Resultados de las Hipótesis

1. ¿Existen tipos de lesiones asociados a mayor fatalidad?
Sí. El análisis de la columna injury reveló que la ubicación de la mordedura es determinante:

Torso: Es la zona con mayor tasa de fatalidad (8.43%).

Cabeza: Presenta una fatalidad del 7.69%.

Extremidades (Brazos/Piernas): Aunque son las más comunes, tienen tasas de fatalidad menores (entre 5.4% y 6.0%).

2. ¿Influye el tipo de actividad en la fatalidad por país?
Sí. Se observaron patrones claros al cruzar actividad y resultado fatal:

En Sudáfrica, el buceo (diving) registra una de las tasas de fatalidad más altas (23.1%).

En Australia, la natación (swimming) presenta un riesgo elevado con un 13.5% de ataques fatales.

El Surfing/Boarding, a pesar de tener el mayor volumen de incidentes en USA, mantiene una tasa de fatalidad muy baja (2.4%).


💡 Recomendaciones:

Priorización de Rescate: Los servicios de emergencia en playas de Australia y Sudáfrica deben enfocarse en zonas de nado y buceo profundo, donde los ataques son menos frecuentes pero más mortales.

Equipamiento de Seguridad: Fomentar el uso de torniquetes y kits de primeros auxilios rápidos para surfistas, ya que la mayoría de sus lesiones ocurren en extremidades.

Educación: Informar a los bañistas sobre el riesgo crítico de ataques en el torso, que aumenta significativamente la probabilidad de un desenlace fatal.

⚠️ Limitaciones y Próximos Pasos:

Limitación: El dataset presenta inconsistencias históricas y un alto número de valores "Unknown" en la columna de fatalidad.

Futuro: Integrar datos sobre especies de tiburones y temperatura del agua para crear un modelo predictivo de riesgo estacional.


👋👋👋👋👋

##Presentación
Slides: https://docs.google.com/presentation/d/1c5t12UAD2h4H993TJcv7VXkVSYojRXvOcbwRUiGdk38/edit?usp=sharing
