<center><h1>TODO List Flutter Application</h1></center>
This Flutter application is designed to manage tasks efficiently using three major folders that play key roles in building the user interface:

<h2>Folder Structure</h2>
<h2>1. model</h2>
The model folder is responsible for defining the structure of the to-do items:
To-Do Item Model:
name: The name of the task that will be displayed.
id: A unique identifier used for functionality like deleting a specific item.
isCompleted: A boolean value indicating whether the task is accomplished.

<h2>2. screens</h2>
The screens folder handles the UI views of the application, containing all the widgets used throughout:
Task List Screen:
Displays the list of tasks with checkboxes and delete icons for each task.
Add Task Screen:
Allows users to add new tasks with input fields for task name.

<h2>3. widgets</h2>
The widgets folder contains reusable components that control the elements inside the task container:
Task Widget:
Manages the layout and behavior of individual tasks displayed in the list.
Includes a checkbox to mark task completion and an icon for deleting the task.
Features
Task Management:
Add, edit, and delete tasks.
Mark tasks as completed or pending.

<h2>Folder Descriptions</h2>
model
This folder defines the data structure for the to-do items used in the application.

screens
Screens are responsible for rendering the user interface of different parts of the app, such as the task list and add task screens.

widgets
Widgets are reusable components that encapsulate UI elements and behavior, making it easier to build and maintain the app's interface.
