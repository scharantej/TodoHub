## Flask Application Design

**Problem**: An application that will connect to a server and can create todo lists.

### HTML files
- `index.html`: The main HTML file of the application.
- `todo_list.html`: A separate HTML file that lists all the todo items.
- `create_todo.html`: A third HTML file that allows the user to create new todo items.

### Routes

- `/`: Renders the `index.html` file.
- `/todo_list`: Renders the `todo_list.html` file and fetches the todo list from the server.
- `/create_todo`: Renders the `create_todo.html` file.
- `/create_todo_item`: A POST route that receives the new todo item from the user and sends it to the server to create a new todo.
- `/delete_todo_item/:id`: A DELETE route that receives a todo item's ID and sends it to the server to delete the todo item.