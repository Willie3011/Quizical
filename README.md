# Quizical - A Simple JavaScript Quiz App

![Quiz Screenshot](https://via.placeholder.com/600x400?text=Quizical+Screenshot) 

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Future Improvements](#future-improvements)
- [License](#license)

## Description

Quizical is a simple, interactive quiz application built with vanilla JavaScript, HTML, and CSS. This project was created as part of my learning journey to understand DOM manipulation, event handling, and state management in JavaScript.

The quiz presents users with multiple-choice questions, tracks their score, and provides feedback at the end based on their performance. It features a clean, responsive design with smooth transitions between screens.

## Features

- **Three distinct screens**: Start screen, Quiz screen, and Results screen
- **Interactive quiz interface**: Answer questions and get immediate visual feedback
- **Score tracking**: Real-time score updates during the quiz
- **Progress indicator**: Visual progress bar shows quiz completion
- **Responsive design**: Works on mobile, tablet, and desktop devices
- **Custom feedback**: Personalized result message based on performance
- **Restart functionality**: Option to take the quiz again without page reload

## Technologies Used

- **Frontend**:
  - HTML5
  - CSS3 (with CSS Variables for theming)
  - JavaScript (ES6)
- **Development Principles**:
  - Semantic HTML
  - Responsive Web Design
  - DOM Manipulation
  - Event Handling
  - State Management

## Installation

This project requires no installation or dependencies. To run it locally:

1. Clone this repository or download the ZIP file:
   ```bash
   git clone https://github.com/willie3011/quizical.git ```
2. Navigate to the project directory
3. Open index.html in your preferred web browser

## Usage

1. Click the "Start Quiz" button on the welcome screen
2. Read each question carefully and select your answer
3. The selected answer will highlight (green for correct, red for incorrect)
4. After a brief pause, the next question will appear automatically
5. After completing all questions, view your results
6. Click "Restart Quiz" to try again

## Customization

### Changing Questions

To modify the quiz questions, edit the quizQuestions array in script.js. Each question object should follow this format: