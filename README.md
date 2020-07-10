# Flask_rest_api
to create an encrypted flask api and set it using heroku

## INSTALLATIONS
```
pip3 install Flast_restful
pip3 install Flask
pip3 install Flask-JWT
pip3 install Flask
pip3 install -U Flask-SQLAlchemy
```
## RUNNING THE API

```
python3 app.py

```

open POSTMAN and the server is set up in the local host and the endpoints are 

<li> /item/<name>  - for getting the items of the individual store requires authentication
<li>/item - getting the complete list of items
<li>/store - getting the items in all the  stores
<li>/store/<name> - getting the item of a particular store
<li>/auth - for getting the JWT token
<li>/register - for registering the user
