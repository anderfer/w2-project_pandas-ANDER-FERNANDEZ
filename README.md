ANDER
# w2-project_pandas-ANDER-FERNANDEZ


La intención del análisis es, suponiendo que la base de datos representa fielmente el total de ataques de tiburones mundial,
ver que actividad, en que pais y para que sexo es más frecuente el ataque de tiburón.

Limpio por tanto las columnas:
 "Sex " : Unicamente se dejan valores válidos, "F", "M", "N", "lli"
 "Activity": Se limpia la columna unificando los nombres
 "Country".: Se limpia con la biblioteca pycountry

Elimino las filas en las que todos los valores son NaN y las filas que tienen al menos dos de los valores del análisis nulos.

Creo una nueva DF a parte con las tres columnas, acumulo para conocer el total de casos para cada combinación posible. Y calculo el porcentaje de cada caso.

Genero un apartado para que el usuario pueda introducir su sexo, pais y actividad y le devuelva el porcentaje de casos que se han dado bajo esos parametros.


Como bonus, veo que en la columna Age, hay varios casos en los que se aportan dos edades, asumiendo que es porque son dos victimas, 
las trato de separar en dos lineas para saber cuantas victimas ha habido, que sería distinto al numero de casos de ataques registrados. 
""No se si lo he hecho bien esto""

Limpio tambien la columna species, Type y Fatal.