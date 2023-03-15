# DataMining2

## Práctica 1
Usa la librería mlextend que nos permita solucionar todos los problemas relacionados con las reglas de asociación. Para ello tendremos que usar el algoritmo Apriori y una serie de métodos para obtener la distinta información que este genera. Replica los pasos de la sección II para responder a los apartados de la sección I.
I) Usaremos la librería con el Dataset Estudiantes.csv que se ha proporcionado. Haz el preprocesamiento necesario para generar el DataFrame de entrada donde las 3 columnas de puntuación estén categorizadas en 4 clases diferentes con rangos de 25 puntos. Realiza el experimento descrito en la sección I creando una serie de experimentos para cada tipo de puntuación.
Prueba al menos tres configuraciones de soporte y frecuencia para cada tipo de puntuación. (1 puntos)
¿Qué diferencias hay entre usar soporte y frecuencia? Respalda la respuesta con datos. (1 punto)
¿Qué tipo reglas desaparecen según la configuración usada y el tipo de puntuación? ¿Por qué? (1 puntos)
Para una de las configuraciones, interpreta algunas de las reglas obtenidas que te hayan resultado curiosas. (2 puntos)
Dadas las mejores configuraciones para cada tipo de puntuación. ¿Existen reglas o patrones que se repitan? ¿Podemos generalizar de alguna manera como se comportan los mejores y peores estudiantes? (2 puntos)
II)
1) Empezaremos obteniendo los itemsets frecuentes para k=1. En este punto necesitaremos obtener el soporte de los itemset. Por lo tanto, se tendrá que usar un método que dado un itemset devuelva su soporte.
2) A partir de k=2.
a. Mostrar los itemset frecuentes candidatos y su soporte.
3) Repetir el proceso 2 hasta que no se generen nuevos itemsets frecuentes.
4) Mostrar todas las posibles reglas con la confianza de cada una de ellas.
5) Listar todas las reglas que sean de alta confianza.
6) Usar los siguientes métodos. Dado un antecesor, devolver todas las reglas que contengan a dicho
antecesor. Dado un umbral mínimo devolver todas las reglas que cumplan con dicha confianza.
7) Utiliza al menos dos representaciones gráficas para representar las reglas obtenidas e interpretar los
datos.


## Práctica 2
Un supermercado cuenta con la información de las compras de uno de sus clientes durante casi 10.000 días. Partiendo de toda esta información, el supermercado ha decidido contratar a un Data Scientist para poder extraer toda la información posible de sus datos. Para ello se dispone del fichero “datos_compras” que tiene para cada uno de los casi 10.000 días, la información de los distintitos productos que ha comprado dicho cliente.
Prueba al menos dos configuraciones de soporte. Para una de ellas, interpreta algunos de los patrones secuenciales que te resulten curiosos. Utiliza al menos dos representaciones gráficas para representar los patrones secuenciales obtenidos e interpretar los datos.
