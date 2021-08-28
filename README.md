# FastAPI

+ FastAPI is a modern, high-performance, batteries-included Python web framework that's perfect for building RESTful APIs.
+ It can handle both `synchronous` and `asynchronous` requests and has built-in support for: 
    + `Data validation`
    + `JSON serialization`
    + `Authentication and Authorization`
    + `OpenAPI documentation`


## Highlights Of FastAPI:
+ Heavily inspired by `Flask`, it has a lightweight microframework feel with support for Flask-like route decorators.
+ It takes advantage of Python type hints for parameter declaration which enables data validation (via Pydantic) and OpenAPI/Swagger documentation.
+ Built on top of `Starlette`, it supports the development of asynchronous APIs.
+ It's fast. Since async is much more efficient than the traditional synchronous threading model, `it can compete with Node and Go with regards to performance`.


## References
- [Pydantic](https://pydantic-docs.helpmanual.io/)
    - Data validation and settings management using python type annotations.



## Setup

Requires python3.6+



## Development
+ Unlike Django or Flask, FastAPI `does not have a built-in development server`. 
+ So, use `Uvicorn`, an `ASGI server`, to serve up FastAPI.


## Deployment



## References
    - [Awesome FastAPI Github Repo](https://github.com/mjhea0/awesome-fastapi)
    - [FastAPI Official Docs](https://fastapi.tiangolo.com/)

