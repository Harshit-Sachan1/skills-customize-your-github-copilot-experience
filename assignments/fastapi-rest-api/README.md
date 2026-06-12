# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a simple REST API using FastAPI by defining routes, handling JSON request data, and returning structured JSON responses.

## 📝 Tasks

### 🛠️ Create API Endpoints

#### Description
Build several FastAPI endpoints to support basic CRUD-style interactions for a simple resource.

#### Requirements
Completed program should:

- Use FastAPI to define an app instance.
- Implement at least two routes: one `GET` route and one `POST` route.
- Return JSON responses from each endpoint.
- Include path or query parameters on at least one route.

### 🛠️ Handle Request Data

#### Description
Accept JSON input in a POST request and use it to create or process a resource.

#### Requirements
Completed program should:

- Define a Pydantic model for request validation.
- Accept JSON request body data in the `POST` route.
- Validate incoming fields automatically with Pydantic.
- Return a confirmation response that includes the received data.

### 🛠️ Document and Test the API

#### Description
Use FastAPI’s automatic docs and test the API routes using a browser or a client tool.

#### Requirements
Completed program should:

- Run with Uvicorn or another ASGI server.
- Expose automatic documentation at `/docs` or `/redoc`.
- Demonstrate calling both endpoints successfully.
- Show example request and response data in the project README.
