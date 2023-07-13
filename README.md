# watchlist
This is my first full stack development project. The project was not deployed to a free server as this is a proof-of-concept. This ensures sufficient credits for the deployment of other web development tools. <br>

The website allows for users to log their favorite movies and videos in a watchlist
<img title="home" src="./imgs/home.png"><br><br><br><br>

1. Displaying a thumbnail of an embedded video for them to relieve their experience of the movie
<img title="play" src="./imgs/movie.png"><br><br>
2. Allow for users to update any properties of movies.
<img title="Edit" src="./imgs/edit.png"><br><br> 

## To start the website
```
pip install -r requirements.txt
```

<br>
Setup your MongoDB database instance and key in the connection string to the .env file - see ".env.example". 

Be sure to:
1. Name your database as 'watchlist'
2. Create a "titles" collection
3. Create a "users" collection to handle user login

<br>
To run the project locally:

```
flask run
```

OR

```
gunicorn: "movie_library.create_app()"
```