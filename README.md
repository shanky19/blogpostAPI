# blogpostAPI

This repository contains the solution for the Blog Post API assignment.

# Requirements

* Python 2.7.11
* Flask 0.10.1 (Python's microweb framework). - pip install flask
* flask_restful module to create a RESTful API. - pip install flask_restful
* sqlalchemy module for handling SQLite queries. - pip install sqlalchemy
* Postman - A Google Chrome app for interacting with HTTP APIs.

# API Implementation

You will need to implement 2 API endpoints for this assignment.

1. `/post` endpoint for POSTing a single blog post
  * Method - POST
  * data -
       title : "blah blah blah"
       body  : "blah blah blah"      
  
2. `/posts` endpoint for GETing all blog posts
  * Endpoint *must* be 
  * Method - GET
  * Content received consists of `post_id`, `title`, and `body` of all posts in an array.

All data exchanged with the API is in JSON format.

# Included in the Repository

An SQLite database `blog.db` includes the table and data (filled while testing).
