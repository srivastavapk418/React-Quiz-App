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