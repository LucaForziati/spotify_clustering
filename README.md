# musicaClasica_recommendation

El presente proyecto tiene como finalidad acercar la música clásica a mas personas. Para ello se pensó en crear un sistema mediante el cual una persona introduce una canción (pop, rock, jazz, etc) y el sistema le devuelve una canción de música clásica que guarde cierta relación con su input.

Para realizar dicha acción se tomaron las features que genera Spotify de las canciones cargadas a su plataforma. Se obtuvo un dataset de Kaggle que cuenta con multiples registros; dentro de los cuales hay música clásica. 

Revisando documentación se consideró que la mejor opción para llegar al objetivo era utilizar la "similitud coseno"; siendo las canciones que mas se acerquen a 1, aquellas recomendables.

La conclusión final del proyecto es que, si bien se alcanzaron resultados interesantes en torno a la relación de una determinada cancion con piezas clasicas, se necesitan de mas parametros para lograr una mayor similitud. Seria interesante lograr extraer fragmentos de melodias de las canciones no clasicas y encontrar similitudes con canciones clasicas y no solo si están en la misma tonalidad o a un tempo parecido. Otro parametro podria ser cadencias de acordes. Sin embargo, obtener dichas similitudes a partir de un analisis mas detallado como previamente se puntualizo, requeriria de tecnicas que escapan al almacenamiento tabulado.
