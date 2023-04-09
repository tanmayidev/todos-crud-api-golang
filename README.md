# todos-crud-api-golang

Creating JSON CRUD API in Go lang using the popular framework Gin

## Assignment

- Create a todo app with following apis:

  - a get request to /todos will show list of all todos
  - a post request to /todos will add a new todo
  - a get request to /todos/:id will show the todo having id passed in query params
  - a patch request to /todos/:id will toggle the value of "completed"

  Todo JSON object example:

  ```json
  {
    "id": 1,
    "title": "Be Kind",
    "completed": false
  }
  ```

## Run the code

`go run main.go`
