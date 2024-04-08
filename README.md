# Text summarization API

![Continuous Integration and Delivery](https://github.com/effr2/text-summarization-service/workflows/Continuous%20Integration%20and%20Delivery/badge.svg?branch=master)
			
Restful API that produces summaries of web pages. 

## API

|  Endpoint |  HTTP Method | CRUD Method  | Result  |
|---|---|---|---|
|  /summaries/ |  GET | READ  | get all summaries  |
|   /summaries/:id/|   GET| READ  |  get a single summary |
| /summaries/			  | POST  | CREATE  |  add a summary |
|/summaries/:id/|	PUT|	UPDATE|	update a summary|
|/summaries/:id/|	DELETE|	DELETE	|delete a summary|

## Tools
This API was built with Python, FastAPI and Newspaper3k Natural Language Processing library. Docker is used to set up the local development environment. Tortoise ORM is used to interact with the PostgreSQL database. Finally, pytest is used for unit and integration tests. 

I decided to use GitHub Actions for CI/CD and Heroku to host the service

This is an ongoing project.
