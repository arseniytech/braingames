[![Actions Status](https://github.com/yeat2007/frontend-project-44/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/yeat2007/frontend-project-44/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/ecd27fab3a02e57a369b/maintainability)](https://codeclimate.com/github/yeat2007/frontend-project-44/maintainability)

# 🧠 Brain Games 2025

A collection of 5 interactive CLI-based games designed to exercise your problem-solving and mathematical thinking skills. Each game presents unique challenges that require quick thinking and logical reasoning.

## 🎮 Available Games

### 1. **Brain Even** — Parity Check
Determine if a number is even or odd.
- **Launch:** `make brain-even`
- **Skills:** Number theory, binary thinking

### 2. **Brain Calc** — Quick Calculations
Solve simple arithmetic problems (addition, subtraction, multiplication).
- **Launch:** `make brain-calc`
- **Skills:** Mental math, operator precedence

### 3. **Brain GCD** — Greatest Common Divisor
Find the GCD of two numbers.
- **Launch:** `make brain-gcd`
- **Skills:** Number theory, Euclidean algorithm

### 4. **Brain Prime** — Prime Number Detector
Identify if a number is prime or composite.
- **Launch:** `make brain-prime`
- **Skills:** Prime numbers, divisibility

### 5. **Brain Progression** — Arithmetic Sequences
Find the missing number in an arithmetic progression.
- **Launch:** `make brain-progression`
- **Skills:** Sequences, pattern recognition

## 🛠 Tech Stack

- **Language:** JavaScript
- **Runtime:** Node.js
- **Build Tool:** Make
- **Testing:** Hexlet Tests
- **Linting:** Code quality checks with CodeClimate

## 📋 Requirements

- Node.js 14+
- Make (for running games)
- npm or yarn

## 🚀 Installation

```bash
git clone https://github.com/arseniytech/braingames.git
cd braingames
npm install
```

## ▶️ How to Play

1. **Run a game** using the Make command above
2. **Answer questions** — you have multiple attempts (3 correct answers to win)
3. **Get feedback** — see if your answer is correct or incorrect
4. **Complete the series** — solve 3 questions in a row to win the game

## 📊 Game Statistics

- **Total Games:** 5
- **Difficulty Level:** Medium
- **Questions per Game:** 3 correct answers to win
- **Time per Game:** ~2-5 minutes

## 🏗 Project Structure

```
braingames/
├── bin/
│   ├── brain-even.js       # Even number game
│   ├── brain-calc.js       # Calculation game
│   ├── brain-gcd.js        # GCD game
│   ├── brain-prime.js      # Prime number game
│   └── brain-progression.js # Progression game
├── src/
│   ├── games/              # Game logic modules
│   └── utils/              # Utility functions
├── Makefile                # Game launch commands
└── package.json            # Dependencies
```

## 💡 Learning Outcomes

Through this project, I practiced:
- ✅ JavaScript fundamentals and logic
- ✅ CLI application development
- ✅ Game loop design and user interaction
- ✅ Code organization and modularity
- ✅ Testing with Hexlet framework

## 🎯 Game Examples

```bash
$ make brain-even
Welcome to Brain Games!
What is the result of 42 + 15?
Your answer: 57
Correct!

What is the result of 72 - 28?
Your answer: 44
Correct!

What is the result of 12 * 6?
Your answer: 72
Correct!

Congratulations, User!
```

## 📝 Notes

- Games are designed for learning and practice
- Suitable for warm-up coding exercises
- Good introduction to algorithm implementation
- Foundation for more complex game development

---

**Author:** Arseniy  
**Status:** ✅ Complete | **CI/CD:** Passing  
**Play it:** `make brain-even` to get started!
