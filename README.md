# FastAPI-prgx-python-challenge


## Description

_Python Challenge to make API using FastAPI_

This challenge showcases as Clean Architecture. Here we have one Entities - Users, Address and Challenge to create CRUD endpoint in REST API. 
Using Python 3.11

## Installation

- Install all the project dependency using [Pipenv](https://pipenv.pypa.io):

  ```sh
  $ pip install pipenv
  $ pipenv install --dev
  ```

- Run the application from command prompt:

  ```sh
  $ pipenv run uvicorn main:app --reload
  ```

- You can also open a shell inside virtual environment:

  ```sh
  $ pipenv shell
  ```

- Open `localhost:8000/docs` for API Documentation

_*Note:* In case you are not able to access `pipenv` from you `PATH` locations, replace all instances of `pipenv` with `python3 -m pipenv`._

## Testing

For Testing, `unittest` module is used for Test Suite and Assertion, whereas `pytest` is being used for Test Runner and Coverage Reporter.

- Run the following command to initiate test:
  ```sh
  $ pipenv run pytest
  ```
- To include Coverage Reporting as well:
  ```sh
  $ pipenv run pytest --cov-report xml --cov .
  ```

## Screenshots

![alt text](https://github.com/Gabean01/prgx-fastapi-backend-challenge/blob/main/resources/swagger_one.PNG)

![alt text](https://github.com/Gabean01/prgx-fastapi-backend-challenge/blob/main/resources/swagger_two.PNG)

![alt text](https://github.com/Gabean01/prgx-fastapi-backend-challenge/blob/main/resources/postman.PNG)