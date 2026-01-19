# Semana2_Shark_Attacks
En este proyecto limpiamos un conjunto de datos desordenado (Shark Attacks) mediante técnicas de data wrangling.

Cosas a cambiar de types: Age a int, date a ?, Year a int? (habría que mantener nulos y usar Int64? df["Year"] = df["Year"].astype("Int64"))
Tenemos datos vacíos, países repetidos con diferentes nombres, faltan años, fechas etc

hipótesis: 
1. Tiene relación el tipo de actividad con recibir más ataques de tiburones?
2. Ciertas lesiones aumentan la probabilidad de que el ataque sea fatal?
3. Temporada del año
4. El número de ataques ha aumentado o disminuido con los años?