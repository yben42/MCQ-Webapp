CSV to MCQ Generator
This project is a web-based tool that allows users to upload a CSV file and instantly generate an interactive multiple-choice quiz. It's a free, privacy-focused alternative for creating custom tests.

Live Demo: https://yben42.github.io/site_p.html

Description
This project was born out of a personal need when popular learning platforms like Quizlet began charging for the ability to create tests from flashcard sets. This tool was built to provide a free and straightforward alternative for students, educators, and lifelong learners.

By formatting your questions and answers in a simple CSV (Comma-Separated Values) file, you can use this web app to generate a clean, interactive quiz. The entire process runs in your browser, meaning your data is never uploaded to a server, ensuring complete privacy.

Features
Free to Use: A no-cost solution for creating quizzes.
File Upload: Easily upload your quiz data using the browser's file picker.
Dynamic Quiz Generation: Instantly transforms CSV data into a fully functional multiple-choice quiz.
Interactive Interface: Select an answer for each question and receive immediate feedback.
Score Tracking: Your final score is displayed upon completing the quiz.
Client-Side Processing: All logic is handled by your browser using JavaScript, ensuring fast performance and privacy.
How to Use
Create your CSV file. The file must have a row for each question. The columns should be structured in a specific order. Please adjust the example below to match the format your script requires. A common structure is:

Question Text,Option A,Option B,Option C,Option D,Correct Answer Letter

Example quiz.csv file:

Code snippet

What is the capital of France?,Paris,London,Berlin,Madrid,A
Which planet is known as the Red Planet?,Venus,Mars,Jupiter,Saturn,B
What is the main ingredient in guacamole?,Tomato,Avocado,Onion,Lime,B
Note: The "Correct Answer Letter" should correspond to the option (e.g., A for the first option, B for the second, and so on).

Go to the website: https://yben42.github.io/site_p.html

Upload the CSV file using the provided button.

The quiz will be automatically generated on the page.

Answer the questions and submit the quiz to see your score.

Technologies Used
This project is built entirely with front-end technologies:

HTML5: For the basic structure and content of the web page.
CSS3: For styling the user interface.
JavaScript: For all the core functionality, including reading the CSV file, generating the quiz questions, and calculating the score.
