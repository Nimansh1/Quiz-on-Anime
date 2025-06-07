# Roblox Style Quiz Game

Welcome to the **Roblox Style Quiz Game** — a colorful, fun, and interactive quiz inspired by the popular Roblox quizzes!

## Description

This is a web-based quiz game featuring characters like Pikachu, Goku, Naruto, Luffy, and Greninja. It showcases vibrant 3D-style text, colorful buttons, and a scoring system to keep track of your progress.

Perfect for fans of anime and Pokémon who want to test their knowledge in a lively and engaging way!

## Features

- Multiple choice questions with 4 options each
- Instant feedback with green/red button highlights for correct and wrong answers
- Score tracking displayed at the top
- Large 3D-style heading and colorful UI for an immersive Roblox vibe
- Responsive design that works on desktop and mobile browsers

## How to Run

1. Download or copy the `index.html` file.
2. Open the file in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Start answering questions and see your score increase!

## How to Play

- Read the question displayed on the screen.
- Click on one of the four answer buttons.
- If your answer is correct, the button turns green; if wrong, it turns red and the correct answer is highlighted.
- Click the "Next Question" button to move on.
- At the end, see your total score out of the number of questions.

## Customization

You can easily add more questions or change existing ones by editing the `quizData` array in the JavaScript section.

Example:
```js
const quizData = [
  {
    question: "New question here?",
    options: ["Option 1", "Option 2", "Option 3", "Option 4"],
    answer: "Option 1"
  },
  // add more questions...
];
