- API_KEY=55bb5aeea2538b26cf848582959d4fc8
- baseURL=https://api.themoviedb.org/3/


#### REQUESTS

##### GET

- Search for a movie: 
  - route : /search/movie
  - params: 
    - api_key
    - query
  - Eg: https://api.themoviedb.org/3/search/movie?api_key=55bb5aeea2538b26cf848582959d4fc8&query=batman
  - [More information](https://developers.themoviedb.org/3/search/search-movies)

- Get movie details:
  - route: /movie/{movie_id}
  - params:
    - api_key
    - movieID
    - [optional] append_to_response=videos (get movie's associated videos) 
  - Eg: https://api.themoviedb.org/3/movie/299537?api_key=55bb5aeea2538b26cf848582959d4fc8&append_to_response=videos
  - [More information](https://developers.themoviedb.org/3/movies/get-movie-details)


If you think this documentation can be improved don not hesitate to contact us ;)

