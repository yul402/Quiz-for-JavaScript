# Project: Quiz-for-JavaScript
This repository contains a JavaScript quiz to test the basic JavaScript semantics.
- link for quiz: password-generator-6n4ju2pp5-yul402.vercel.app


## Homepage:
Home page contains "View Score" button, "Time Left" display and "User Guidance" sections. 

- "View Score": Located at top left corner. The webpage will be direct to "View Score" webpage after user clicking on the text.
- "Time Left": the display show remaining time for this quiz. If user answer the question incorrectly, 10s will be deducted as penalty. The quiz stops when "Time left" is 0 second and next question will not be shown if only 2s left in timer as the transition between questions takes 1s. The initial set up for quiz is 75s.
- "User Guidance": this section is located at the center of the webpage. It contains the guidance for the quiz and once user click on the "Start Quiz" button, the count down timer will start to run and question will be shown.

Figure below demonstrates homepage:

![Alt text](/Assets/Quiz_01.png?raw=true "Homepage")

### Load Question: 
Question will be loaded after user click on the "Start Quiz" button. There are 8 JavaScript questions from "W3 Schools" contained in this application. All of them are single section multiple choice question and each of them takes 12.5 points out of 100 points. 

Question will be loaded one by one after user finishing and checking previous question's ansewer. Figures below illustrates the answer check play.

- When user is correct: 
![Alt text](/Assets/Quiz_02.png?raw=true "Correct Answer")
-when user is wrong: (10s is deducted from "Time Left")
![Alt text](/Assets/Quiz_03.png?raw=true "Wrong Answer")

## Result display:
Final score appears when "Time Left" is 0s. In this page, user can choose to enter his/her initial to submit the score. The submitted score will be stored in localStorage for future reference.
After collecting valid password specification, a password will be generated. The generated password met user's requirement and will be shown in the website.
![Alt text](/Assets/Quiz_04.png?raw=true "Result Display")

## View Score:
User will be direct to "View Score" webpage to check all scores submitted by user. They can choose to play the quiz again by clicking "Go Back" button.

![Alt text](/Assets/Quiz_05.png?raw=true "View All Scores")
