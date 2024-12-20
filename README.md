# Netlify link : https://velvety-travesseiro-45497c.netlify.app/
# Addition-Quiz-Game-
This is a simple Addition Quiz Game built with HTML, CSS, and JavaScript. It challenges users with randomly generated addition problems, keeps track of their score, and saves the score using browser local storage for persistent gameplay.
# Features
Dynamic Question Generation: Randomly generates addition problems using numbers between 1 and 1000.
Score Tracking: Displays the user’s current score, which updates after every question.
Persistent Score: Utilizes browser local storage to maintain the score across page refreshes.
Interactive UI: A visually appealing and user-friendly interface built with HTML and CSS.
# File Structure
arduino
Copy code
|-- index.html    // Main HTML file for the game's structure
|-- style.css     // CSS file for styling the UI
|-- script.js     // JavaScript file for game logic
How It Works
Random Addition Questions:

Two random numbers (num1 and num2) are generated using Math.ceil(Math.random() * 10).
The question is displayed in the format: "What is X plus Y?".
User Interaction:

Users enter their answer in an input field and submit it using a form.
Score System:

Correct answers increase the score by 1.
Incorrect answers decrease the score by 1.
Persistent Storage:

The score is stored in the browser’s local storage, allowing users to retain their score even after a page refresh.
Dynamic Updates:

The game dynamically updates the question, score, and input field without reloading the page.
