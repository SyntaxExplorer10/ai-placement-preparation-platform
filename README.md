# AI Placement Preparation Platform
A browser-based AI Placement Preparation Platform for practicing aptitude and programming questions, taking timed quizzes, tracking performance, and generating personalized practice questions.


A browser-based placement preparation platform designed to help students practice aptitude and programming questions, take timed quizzes, track performance, and receive personalized practice recommendations.

## Features

* Student registration and login
* Admin and student roles
* Aptitude and programming question bank
* Category and difficulty-based filtering
* Timed quizzes with automatic scoring
* Quiz performance history
* Wrong-answer explanations
* Personalized practice recommendations
* AI-generated practice questions using local templates
* Admin question management
* Admin category management
* Student performance overview
* Browser-based data persistence using `localStorage`
* Responsive user interface

## Technology Stack

* HTML5
* CSS3
* JavaScript
* Browser LocalStorage

## Modules

### Student

Students can:

* Register and log in
* Practice questions
* Filter questions by category and difficulty
* Take timed quizzes
* View quiz results
* Review incorrect answers
* Get explanations for mistakes
* View performance history
* Generate personalized practice questions

### Admin

Administrators can:

* View platform statistics
* Add and delete questions
* Add and delete categories
* View registered students
* View student quiz performance

## AI Features

The current version includes a **simulated local AI engine**.

It provides:

* Wrong-answer explanations
* Weak-topic identification
* Personalized question generation

The AI functionality currently uses predefined rules and question templates rather than an external AI API.

## Demo Credentials

### Admin

```text
Email: admin@placement.com
Password: admin123
```

### Student

```text
Email: student@placement.com
Password: student123
```

These credentials are for demonstration purposes only.

## Data Storage

This project currently runs entirely in the browser.

User accounts, quiz results, answers, and other application state are stored using:

```text
localStorage
```

Therefore, the application does not currently use a backend database or server-side authentication.

## Project Architecture

The application is implemented as a single-page browser application inside `index.html`.

The main components include:

```text
Authentication
      ↓
Student Dashboard
      ↓
Practice / Quiz / History / AI Assistant

Admin Dashboard
      ↓
Questions / Categories / Students
```

## Future Improvements

Planned improvements include:

* Spring Boot backend
* REST APIs
* Oracle/MySQL database
* Secure authentication
* Password hashing
* Real AI API integration
* Student progress analytics
* More aptitude and programming questions
* Coding practice module
* Company-specific placement preparation
* Deployment with a production backend

## Disclaimer

This project is an educational/demo application. Authentication and data storage are implemented on the client side and should not be considered production-grade security.

## Author

Developed as a placement preparation project to explore frontend development, JavaScript application architecture, quiz systems, performance tracking, and AI-assisted learning concepts.

## 🚀 Live Demo

👉 [AI Placement Preparation Platform](https://ai-placement-prep-site.netlify.app/)
