# watchlist
This is my first full stack development project. The website allows for users to log their favorite movies and videos in a watchlist, displaying a thumbnail of an embedded video for them to relieve their experience of the movie, and for users to update any properties of movies. 

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

<br> OR

```
gunicorn: "movie_library.create_app()"
```

<br>