A simple to-do list application built using React. This application allows users to add new tasks, toggle task completion, remove tasks, and filter tasks based on their completion status. It also supports sorting tasks in alphabetical order.

Features:
Add new tasks,
Toggle task completion,
Remove tasks,
Filter tasks based on completion status, Sort tasks in alphabetical order.

Adding a new task: 
Open the ToDoList application.
Enter a new task in the "Add new task" input field.
Click the "Add" button.
Verify that the new task is displayed in the list.

Open the ToDoList.js file.
Look for the handleAddTask function, which is responsible for adding a new task.
This function is called when the user clicks the "Add" button in the application.
When the function is called, it prevents the default form submission behavior and checks if the newTask state is not an empty string.
If the newTask state is not empty, it creates a new task object with a unique id (generated using Date.now()), the text from the newTask state, and a completed property set to false.
It then updates the tasks state using the setTasks hook by spreading the existing tasks and adding the new task to the array.
Finally, it resets the newTask state to an empty string.


