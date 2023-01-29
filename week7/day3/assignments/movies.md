# Assignment - Movies Website

In this assigment you are going to allow a user to keep track of their movie collection. Create a website which will allow the user perform the following features: 

- Ability to add a movie (title, description, genre, posterURL) 
- Ability to view all movies 

- Ability to delete a movie 

- Ability to filter movies based on the genre 

- Ability to go to movie details page

- Expose all your movies by creating a Web API route at /api/movies which should return all the movies in JSON format. 

**Routes:** 

* /movies - View all movies (Show the poster image and the name of the movie on this age) 

* /movies/create - POST - Add a new movie 

* /movies/delete - POST - Deletes a movie 

* /movies/:movieId - Details about the movie (Show poster image, title, genre and description on this page) 

* /movies/genre/:genre - Show movies based on genre 

* Use Express Router to create movies.js route which will contain all the routes of the movies 

**HARDMODE:** 

- Allow the user to upload image from their computer to your server's folder instead of asking them to put the URL of the image. 
