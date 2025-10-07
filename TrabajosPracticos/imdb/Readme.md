Las columnas son:

- id: Identificador único asignado a cada película o serie de televisión dentro del dataset. Este ID permite distinguir cada entrada de las demás.

- title: Título principal de la película o serie de televisión tal como se conoce comúnmente.

- type: Indica el tipo de contenido al que corresponde la fila, generalmente puede ser "movie" (película) o "show" (serie de televisión).

- description: Un breve resumen o sinopsis del argumento o la premisa de la película o serie de televisión.

- release_year: Año en el que la película fue estrenada o en el que se emitió el primer episodio de la serie de televisión.

- age_certification: Clasificación por edad o certificación de contenido (por ejemplo, PG-13, R, TV-MA). Esta información indica la audiencia para la que se considera apropiado el contenido. Puede estar ausente si no se dispone de esta información.

- runtime: Duración total de la película en minutos o la duración promedio de un episodio de la serie de televisión en minutos.

- genres: Lista de los géneros cinematográficos o televisivos a los que pertenece la película o serie (por ejemplo, drama, action, thriller, european). Puede haber múltiples géneros asociados a una misma entrada.

- production_countries: Lista de los países que estuvieron involucrados en la producción de la película o serie de televisión.

- seasons: Número total de temporadas que tiene una serie de televisión. Esta columna generalmente solo aplica a las entradas donde la columna "type" es "show". Para las películas, esta columna podría estar vacía o contener un valor nulo.

- imdb_id: Identificador único asignado a la película o serie de televisión dentro de la base de datos de IMDb (Internet Movie Database). Este ID permite enlazar la entrada con su página correspondiente en IMDb.

- imdb_score: Puntuación o calificación promedio que los usuarios de IMDb han otorgado a la película o serie de televisión. Generalmente es un valor numérico entre 0 y 10.

- imdb_votes: Número total de votos o calificaciones que la película o serie de televisión ha recibido por parte de los usuarios de IMDb. Un mayor número de votos puede indicar una mayor popularidad o un consenso más sólido sobre la puntuación.

- tmdb_popularity: Un valor numérico que representa la popularidad de la película o serie de televisión en la base de datos de TMDB (The Movie Database). Este valor se calcula en base a diversas métricas de actividad de los usuarios en la plataforma.

- tmdb_score: Puntuación o calificación promedio que los usuarios de TMDB han otorgado a la película o serie de televisión. Generalmente es un valor numérico entre 0 y 10.
