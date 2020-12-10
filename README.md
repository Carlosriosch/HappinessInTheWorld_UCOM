# HappinessInTheWorld_UCOM
 En este trabajo se estudia el data set Happiness in the World de Kaggle, que tiene el objetivo de crear un algoritmo que prediga cuál es el Score de Felicidad de un país. En primer lugar se realizó la limpieza y analytica de los datos obteniendo que año a año no existen variaciones considerables y que el factor que más influye en el score de felicidad es el PIB de un país. Seguidamente al observar el comportamiento lineal de los datos con respecto al target se decidió utilizar una regresión lineal múltiple para predecir el Score de Felicidad, la ecuación obtenida participó de la competencia de Kaggle obteniendo un lugar entre 5to y 6to, con una varianza de 0.78. Finalmente se aplicó el método K-means para agrupar en clusters los países semejantes entre sí. Mediante el análisis del método de Elbow, el silhoutte score y principalmente el Calinsky-Harabazs score se obtuvo que el hiperparámetro óptimo es k=4.
