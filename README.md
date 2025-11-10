# 🧠 React Quiz App

A dynamic, timed multiple-choice quiz built with **React**, **Context API**, and **useReducer**.  
This project uses a local fake API (Vercel’s Serverless Functions) to serve quiz questions from `data/questions.json`.

---

## 🔗 Live demo
[➡️ Click to view live demo](https://react-quiz-app-one-gilt.vercel.app/)

---

## ✨ Features
- Timed quiz (configurable seconds per question).  
- Question/option UI with instant scoring.  
- Progress, timer, and final score screens.  
- High score tracking during session.  
- Error & loading states.  
- Local fake API using `Vercel’s Serverless Functions` (serves `/questions`).

---

## Tech stack
- React (Create React App)  
- Context API + `useReducer` for global state  
- Vercel's serverless functions for local fake API (`data/questions.json`)  
- JavaScript (ES6+) and CSS

---

## 📸 Screenshots
<img width="1920" height="850" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/547753d8-35c3-4d36-90c1-d8183be319e3" />
<img width="1920" height="852" alt="Screenshot (87)" src="https://github.com/user-attachments/assets/fb048c17-31db-4b14-9ecd-5ea5636c2956" />
<img width="1920" height="848" alt="Screenshot (88)" src="https://github.com/user-attachments/assets/423ffa03-2f7d-43d5-a518-4172bf76211e" />
<img width="1920" height="861" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/a17f1c8d-26f5-4385-a201-09ec72e618a9" />

---

## 📂 Project structure
- src/contexts/QuizProvider.jsx — fetches data from /api/questions.js and contains the reducer & timer logic.
- data/questions.json — the dataset served by serverless functions.
- src/components — UI components: Header, Main, Question, NextButton, Progress, FinishScreen, Timer, etc.

## 🧑‍💻 What I learned / Practiced
- Global state with Context + useReducer (finite-state flow: loading → ready → active → finished).
- Side effects with useEffect (fetching questions, timer).
- Building robust UI states (loading, error, active quiz, finished).
- Using json-server (but vercel's serverless function for deployment) for quick, local API mocking and development.

---

Made by **Prateek** with ❤️ using React and Context API
