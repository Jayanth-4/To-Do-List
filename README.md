To-Do List Web Application : https://jayanth-4.github.io/To-Do-List/
--------------------------

Project Overview:-
------------------
This is a simple yet functional To-Do List web application built using HTML, CSS, and JavaScript. The application allows users to add tasks, mark them as completed, and remove tasks from the list. All tasks are saved in the browser's localStorage, so the list persists even after the page is refreshed.

Features:-
-----------
Add Tasks: Users can input their tasks into a text field and click the "Add" button to add tasks to the list.
Mark as Completed: Tasks can be marked as completed by clicking on them. Completed tasks will appear with a strikethrough.
Delete Tasks: Each task has a delete button ("×") that allows users to remove tasks from the list.
Persistent Data: The list data is stored in localStorage, meaning that it persists even after the browser is refreshed or reopened.

How It Works:-
----------------
Task Addition: Users input their task in the input box and click the "Add" button. A new task is added to the list and displayed dynamically.
Task Completion: Clicking on a task toggles its "checked" state, adding a strikethrough and changing the style.
Task Removal: Each task has a delete button (marked with "×"). When clicked, it removes the task from the list.
LocalStorage: The saveData function saves the current state of the list in the browser's local storage, and the showTask function retrieves this data on page load.

Technologies Used:-
-------------------
HTML5: Structure of the web application.
CSS3: Styling and layout of the To-Do List. The app includes background images and responsive design.
JavaScript: Handles the logic of adding, marking, deleting tasks, and interacting with the local storage.

File Structure:-
-----------------
/To-Do-List
│
├── /Images
│   ├── Jay_logo.png
│   ├── icon.png
│   └── checked.jpg
│
├── index.html
├── style.css
└── response.js

Setup Instructions:-
---------------------
Clone the repository:
git clone https://github.com/Jayanth-4/todo-list.git
Navigate to the project folder and open the index.html file in your browser to view the app.

Customization:-
----------------
You can modify the background image and styling by updating the style.css file.
The logo and icons can be replaced in the /Images folder to personalize the app.

Contact:-
----------
If you have any questions or suggestions, feel free to reach out at jayanthmourya27@gmail.com.
