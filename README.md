## About Online MCQ Quiz System in PHP Laravel and Javascript (AJAX)

This Online MCQ Quiz System is a web application based on Laravel (PHP) that can help to understand how to create an online quiz system using Laravel or PHP. Currently, The initial version has the following features:

- Create MCQ Quiz and Add Expiry Date
- Give Duration of the Quiz
- Add Question and Define Correct Answers
- Delete and edit Question
- View Quiz and Results
- Signup as Student
- Participate Any MCQ Quiz and Get Instant Result
- Timer
- If Quiz Time is over, No submission will be taken
- Custom Authentication System (Not using Laravel default Auth)


## How to Run this Project
Running this project is very easy. To do it, you can follow these steps.

- Make Sure You Have Installed Composer on Your System
- Then, Download this project and open it with any editor.
- Now, type composer update in the terminal and hit enter. If your editor doesn't have built in terminal, you can use default terminal of your OS.
- Rename the .env.example to .env and put your database details here.
- Then run this command "php artisan migrate" and then, this one ``` "php artisan db:seed" ```
- Now, You can run your project from local host. However, You also can use this command ``` "php artisan serv" ``` to test this project.
- The default username is "admin" and password is "123456". Use this credential to login and create quiz.
- Student Accounts are not created automatically. So, You can signup for one to test.

You can modify/customize this project. I hope this project will help to understand how to build a custom link shortening application with Laravel.

## A Few Screenshots

![Alt text](public/screenshot/quizlist.png?raw=true "Title")
![Alt text](public/screenshot/quizresult.png?raw=true "Title")
![Alt text](public/screenshot/addQuiz.PNG?raw=true "Title")
![Alt text](public/screenshot/listQuiz.PNG?raw=true "Title")
![Alt text](public/screenshot/login.PNG?raw=true "Title")
