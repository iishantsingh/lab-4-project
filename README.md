# 📘 Prompt Quizzer – A JavaScript Quiz Game

This repository contains a simple JavaScript-based quiz game that runs entirely in the browser console.
The quiz asks a series of predefined questions, takes user input through prompt(), provides instant feedback using alert(), and finally displays the total score.


# 🚀 Features

1. Uses arrays, loops, and functions

2. Takes user input using prompt()

3. Provides immediate feedback (Correct! / Incorrect!)

4. Normalizes input using toLowerCase() and trim()

5. Tracks score throughout the game

6. Shows final score at the end

7. Runs inside the browser console without needing HTML/CSS


# 📂 Project Structure

Lab-4/
│── index.html
│── script.js

## index.html

Contains a basic HTML file that loads the file. [script.js](https://github.com/user-attachments/files/23839034/script.js)

## script.js

Includes the quiz questions array and the full quiz logic.


# 🧠 How the Quiz Works

1. A predefined list of questions and answers is stored in an array.

2. A function runQuiz() loops through each question.

3. User enters answers through prompt().

4. Input is normalized using:

toLowerCase()

trim()

5. Correct/incorrect feedback is given immediately via alert().

6. Score is updated.

7. After the last question, the final score is displayed.


# 📝 Code Overview

## Quiz Questions Array

Stores all questions and correct answers.

## runQuiz() Function

Handles the entire quiz logic, including:

1. Asking questions

2. Checking answers

3. Scoring

4. Final result display


# ▶️ How to Run the Quiz

1. Open index.html in any web browser.

2. Right-click → Inspect → go to Console.

3. The quiz will automatically start because runQuiz() is called at the end of script.js.

4. Answer each question in the prompt pop-ups.

5. Check your final score when the quiz ends.


# 📸 Expected Output

Below are the screenshots showing how prompts and alerts appear during the quiz:

![lab4 output1](https://github.com/user-attachments/assets/53487f55-9785-4b8a-af96-72bb6a9ffcfd) 

![lab4 output2](https://github.com/user-attachments/assets/5733784d-f923-4cf6-b5b4-74c6bc8df6b9)


# 🎯 Learning Outcomes

By completing this project, you learn to:

1. Use arrays to store multiple values

2. Use loops to repeat actions

3. Create reusable functions

4. Use prompt() and alert() for I/O

5. Compare strings reliably using toLowerCase() and trim()

6. Run and test JavaScript inside the browser console


# 📌 Improvements 

1. Add more questions

2. Add multiple-choice options

3. Add a timer

4. Add hints for wrong answers

5. Store high scores using Local Storage

6. Add a restart option


# 👤 Author

Ishant Singh

2501410067

BTech (CyberSecurity) Semester 1
