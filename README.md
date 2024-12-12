# Module 14 Mini-Project: GraphQL API for a Movie Database
Data Schema Creation with SQLAlchemy:
Create a relational database schema using SQLAlchemy to represent movie and genre entities:
Define a table for movies with columns for movie ID, title, description, release year, etc.
Define a table for genres with columns for genre ID and name.
Define appropriate table structures, schemas, constraints, and foreign key relationships in the database schema
Implementation of Mutations for Genres and Movies:
Develop GraphQL mutations to enable the creation, updating, and deletion of genres:
createGenre: Mutation to create a new genre.
updateGenre: Mutation to update an existing genre.
deleteGenre: Mutation to delete an existing genre.
CreateMovies: Mutation for creating a movie.
UpdateMovies: Mutation to update an existing movie
DeleteMovies: Mutation to delete an existing genre.
Ensure proper validation of input data for genre mutations:
Validate that the genre name is not empty and does not exceed a certain length.
Validate that the genre ID provided for update and delete mutations exists in the database.
Relationships Between Movies and Genres:
Implement GraphQL queries to retrieve movies based on genres and vice versa:
getMoviesByGenre: Query to retrieve a list of movies belonging to a specific genre. Accepts input parameter for the genre ID.
getGenreByMovie: Query to retrieve the genre(s) associated with a specific movie. Accepts input parameter for the movie ID.
Ensure that relationships between movies and genres are handled correctly. For example, ensure there aren't any issues if a movie has multiple genres or if a genre can be found on multiple movies.
GitHub Repository:
Create a GitHub repository for the project and commit code regularly.
Maintain a clean and interactive README.md file in the GitHub repository, providing clear instructions on how to run the application and explanations of its features.
Include a link to the GitHub repository in the project documentation.

Just run the app.py, and use mutation to create a movie and genre. Once created you can use mutation to Delete and Update your movie/genre. Then you can use query "movies" and "genres"
to GET your tables. You can also use the "mg" query to receive the genres by movieId and you can use the "gm" query to receive the movies by genreId.
