# WebProject
# Combat Codex

Combat Codex is a React web application built with Vite. It is a modern combat-sports educational platform focused on martial arts knowledge, fight intelligence, training discussions, myths, and entertainment.

The project was created as a university web development project to demonstrate the main concepts of React, including components, props, state management, hooks, routing, forms, list rendering, CRUD operations, and localStorage persistence.

---

## Project Description

Combat Codex is designed as an interactive platform for users interested in combat sports and martial arts. The application includes quizzes, educational myth explanations, a humorous simulator, a community forum, and a simulated local fight streaming page.

The app does not encourage real violence. Its purpose is educational, sportive, and entertainment-based.

---

## Main Features

- Home page with navigation cards
- Martial Art Quiz that recommends a martial art based on user answers
- Fight IQ Quiz with scenario-based combat sports questions
- Myth Buster page explaining common fighting myths
- Gorilla Simulator for humorous fictional results
- Community Forum with full CRUD functionality
- Local Fight Streams page with simulated match cards and comments
- localStorage persistence for forum posts and stream comments
- Responsive dark-themed user interface

---

## Technologies Used

- React
- Vite
- JavaScript
- React Router
- CSS
- HTML5
- localStorage

---

## React Concepts Demonstrated

This project demonstrates the following React concepts:

- React components
- Reusable components
- Props
- useState
- useEffect
- React Router
- Forms
- List rendering with `.map()`
- Conditional rendering
- CRUD operations
- localStorage data persistence
- Organized folder structure

---

## Pages / Routes

The project contains the following main pages:

- `/` - Home Page
- `/martial-art-quiz` - Martial Art Quiz
- `/fight-iq` - Fight IQ Quiz
- `/myth-buster` - Myth Buster
- `/gorilla-simulator` - Gorilla Simulator
- `/forum` - Community Forum
- `/streams` - Local Fight Streams

---

## Folder Structure

```txt
src/
│
├── components/
│   ├── Navbar.jsx
│   ├── FeatureCard.jsx
│   ├── MythCard.jsx
│   ├── ProgressBar.jsx
│   ├── PostCard.jsx
│   └── StreamCard.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── MartialArtQuiz.jsx
│   ├── FightIQQuiz.jsx
│   ├── MythBuster.jsx
│   ├── GorillaSimulator.jsx
│   ├── CommunityForum.jsx
│   └── LocalFightStreams.jsx
│
├── data/
│   ├── myths.js
│   ├── fightIqQuestions.js
│   ├── martialArtQuestions.js
│   └── streams.js
│
├── utils/
│   └── storage.js
│
├── App.jsx
├── main.jsx
└── index.css
