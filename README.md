# -MCA-PBL-WEB
An interactive Online Quiz Application built with HTML, CSS, and JavaScript, featuring dynamic quiz questions, API integration, countdown timer, question navigation, automatic scoring, performance analysis, and certificate generation.


# 🎓 Online Quiz Application

An interactive and user-friendly web-based quiz application developed using **HTML, CSS, and JavaScript**. It allows students to participate in multiple-choice quizzes, select different topics, track their progress, and view their results with grades and certificates.

## 🌐 Live Demo

**Try the application:**  
https://simplequizeapplication.netlify.app/

## 📌 Project Overview

The Online Quiz Application is designed to provide a simple platform for students to test their knowledge through multiple-choice questions.

Users can enter their details, select a quiz topic, choose the number of questions, and start the quiz. The application displays questions with a countdown timer and provides automatic score calculation after quiz completion.

## ✨ Features

- Student name and student code input.
- Multiple quiz topic selection.
- Custom question count selection.
- Dynamic question loading through an external API.
- Multiple-choice questions with randomized answer options.
- Countdown timer for each question.
- Previous and Next question navigation.
- Save selected answers.
- Question navigation panel.
- Automatic score calculation.
- Result analysis with percentage and grade.
- Performance progress bar.
- Certificate generation and printing.
- Responsive user interface.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of web pages |
| CSS3 | Styling and responsive design |
| JavaScript | Quiz logic and interactivity |
| Fetch API | Retrieving quiz questions |
| Local Storage | Storing user details and quiz results |
| External Quiz API | Providing quiz questions |
| Visual Studio Code | Development environment |

## 📂 Project Structure

```text
Online-Quiz-Application/
│
├── index.html
├── quiz.html
├── result.html
├── certificate.html
│
├── css/
│   └── style.css
│
├── js/
│   ├── login.js
│   ├── quiz.js
│   ├── result.js
│   └── certificate.js
│
└── README.md
```

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Extract the project folder if downloaded as ZIP.
3. Open the folder in Visual Studio Code.
4. Configure your quiz API credentials in the appropriate JavaScript configuration, if required.
5. Open `index.html` using Live Server or a local web server.
6. Enter your details and select a quiz topic.
7. Start answering the questions.

## 🔑 API Integration

The application uses an external quiz API to retrieve multiple-choice questions dynamically.

JavaScript Fetch API is used to send requests and receive question data in JSON format.

**Note:** Do not publish your private API key in a public GitHub repository. Use a secure backend or proxy for production applications.

## 💾 Data Storage

The application uses browser `localStorage` to store information such as:

- Student name
- Student code
- Selected subject
- Quiz answers
- Score and total questions

No custom backend database is used in the current version.

## 🎯 Future Enhancements

- Student registration and login system.
- Database integration.
- Leaderboard and ranking system.
- Admin dashboard for managing questions.
- Detailed performance analytics.
- More quiz categories and difficulty levels.

## 👨‍🎓 Project Information

**Project Name:** Online Quiz Application  
**Course:** Master of Computer Applications (MCA)  
**Department:** Computational Sciences  
**University:** Brainware University  
**Development Technologies:** HTML, CSS and JavaScript  
**Project Type:** Academic Group Project

## 👥 Project Contributors

- Sumi Bera
- Suvho Dhara
- Swati Madduney
- Pranay Jana
- Apurba Kuiti
- Jeet Sarkar

## 📜 License

This project was developed for academic and educational purposes.
