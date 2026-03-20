**Firebase Todo App**

A simple Todo List web application built using HTML, CSS, JavaScript, and Firebase Realtime Database.
This app allows users to add and view their tasks in real time, with data stored in Firebase.
---------------------------------------------------------------------------------------------
Features

Add new todos easily.

Real-time syncing with Firebase Realtime Database.

Automatically fetches and displays todos.

Hosted on GitHub Pages.

Clean and minimal UI.
----------------------------------------------------------------------------------------------------
 Tech Stack

Frontend: HTML, CSS, JavaScript

Backend/Database: Firebase Realtime Database

Hosting: GitHub Pages
------------------------------------------------------------------------------------------------------

Setup & Installation

Clone this repository:

git clone (https://github.com/aeron-gh/firebaseTODO.git)


Open the project folder.

Create a Firebase Realtime Database project and get your config.

Replace the Firebase config inside script.js with your own.

Open index.html in a browser (or host it on GitHub Pages).
-------------------------------------------------------------------------------------------------------------------------------------

How It Works

On page load, the app listens to Firebase using onValue() and fetches todos in real-time.

When you add a todo, it pushes the data into Firebase using push().

Firebase notifies the app, and the todo list updates instantly.

//*
Current Behavior (Important)
All users share the same global todo list.
Since there is no authentication or user identification, tasks added by any user are visible to everyon
*//

--Contributing--
Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.
