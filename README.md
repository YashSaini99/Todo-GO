# Todo App in Go 📝

Welcome to the Todo App built with Go! This application helps you manage your tasks efficiently. You can add, complete, delete, load, and store tasks. The app uses JSON for storage to keep track of your todos.

## Features 🚀

- **Add Tasks:** ➕ Add new tasks to your todo list.
- **Complete Tasks:** ✅ Mark tasks as completed.
- **Delete Tasks:** ❌ Remove tasks from the list.
- **Load Tasks:** 📂 Load tasks from the JSON file.
- **Store Tasks:** 💾 Save tasks to a JSON file.

## Screenshot

![App Screenshot](https://github.com/YashSaini99/Todo-GO/blob/main/Screenshot.png)

## Requirements 📋

- Go 1.18 or higher
- Basic knowledge of Go programming

## Installation ⚙️

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/YashSaini99/Todo-GO.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo
   ```

3. Build the application:

   ```bash
   go build -o ./cmd/todo
   ```

4. Run the application:

   ```bash
   ./todo -list
   ```

## Usage 🛠️

### Add a Task

To add a task, run the following command:

```bash
./todo -add "Task Description"
```

### Complete a Task

To mark a task as completed, use the following command with the task ID:

```bash
./todo -complete=TASK_ID
```

### Delete a Task

To delete a task, use the following command with the task ID:

```bash
./todo -delete=TASK_ID
```

### List Tasks

To list all tasks, simply run:

```bash
./todo -list
```

## JSON Storage 📁

The tasks are stored in a JSON file named `tasks.json`. You can modify or view this file to see your stored tasks.

## Contributing 🤝

Contributions are welcome! If you have suggestions or improvements, please fork the repository and create a pull request.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](https://github.com/YashSaini99/Todo-GO/blob/main/LICENSE) file for details.
