# Smart Interview Prep Portal

A complete front-end interview preparation web application built with HTML, CSS, and JavaScript.

## Features
- **6 Topic Categories**: HTML, CSS, JavaScript, Data Structures, Aptitude, HR Interview
- **Quiz Mode**: Timed quizzes with instant feedback and score tracking
- **Study Mode**: Browse interview Q&A with reveal-on-click answers
- **Dashboard**: Statistics, recent activity, and topic progress bars
- **Results Page**: Score ring animation, wrong answer review, full history
- **User Auth**: Register/Login with localStorage (no backend needed)

## Project Structure
```
smart-interview-prep-portal/
├── index.html        Home page
├── login.html        Auth page (login + register)
├── dashboard.html    User dashboard with stats
├── topics.html       Topic selection grid
├── quiz.html         Quiz + Study mode (dynamic)
├── results.html      Results + History
├── css/style.css     All styles (glassmorphism, animations)
├── js/questions.js   Full question database (60 quiz + 60 interview Q&As)
└── js/script.js      Application logic
```

## How to Run
1. Open `index.html` in any browser (no server needed!)
2. Click "Get Started" or use **Demo Login**
3. Or register your own account and start practicing

## Tech Stack
- Vanilla HTML5, CSS3, JavaScript (ES6+)
- Google Fonts: Syne + DM Sans
- localStorage for persistence (no backend)
- CSS custom properties, Flexbox, Grid
- CSS animations and glassmorphism UI
