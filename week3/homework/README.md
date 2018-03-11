# HackYourFuture Node.js Week 3 - Homework

### Assignment

Read through the code from the lecture, make sure you understand the flow of the
program.

Add three more actions:

### `clearTodos` (`DELETE /todos`)

Clears the list of to-dos

### `markAsDone` (`POST /todos/:id/done`)

Sets the `done` flag of a single to-do to `true`

### `markAsNotDone` (`DELETE /todos/:id/done`)

Sets the `done` flag of a single to-do to `false`

## Requirements

- All requests that need a body should be in JSON format, and follow the request
  structure of the other actions
- All responses should be in JSON format, and follow the response structure of
  the other actions
- Follow the anatomy of the project
- Make sure your code is [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- Follow the REST design principles: use the proper method, response status
  codes, and consistent URL paths
- Test your API using Postman