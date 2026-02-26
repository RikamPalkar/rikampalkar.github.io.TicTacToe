# 🎮 Tic-Tac-Toe AI with MinMax Algorithm

<div align="center">

![Tic-Tac-Toe AI](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.2.2-3178C6?style=for-the-badge&logo=typescript)
![Vite](https://img.shields.io/badge/Vite-5.0.8-646CFF?style=for-the-badge&logo=vite)

**An intelligent Tic-Tac-Toe game featuring an unbeatable AI powered by the MinMax algorithm**

[Live Demo](https://rikampalkar.github.io/TicTacToe) • [Report Bug](https://github.com/RikamPalkar/TicTacToe/issues) • [Request Feature](https://github.com/RikamPalkar/TicTacToe/issues)

</div>

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [The MinMax Algorithm](#the-minmax-algorithm)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [About the Developer](#about-the-developer)
- [Learning Resources](#learning-resources)
- [License](#license)
- [Connect](#connect)

---

## 🎯 About The Project

This is an advanced implementation of the classic Tic-Tac-Toe game that challenges you to beat an unbeatable AI opponent. The AI uses the **MinMax Algorithm**, a decision-making algorithm commonly used in game theory and artificial intelligence, to calculate the optimal move at every turn.

Unlike traditional Tic-Tac-Toe implementations with random or basic AI, this version provides a true challenge where the AI never makes a mistake. The best you can hope for is a draw!

### Why This Project?

This project serves multiple purposes:

- **Educational**: Demonstrates practical implementation of the MinMax algorithm
- **Interactive**: Provides a hands-on way to understand AI decision-making
- **Portfolio Piece**: Showcases modern web development practices with React, TypeScript, and advanced algorithms
- **Challenge**: Tests your strategic thinking against perfect play

---

## 🧠 The MinMax Algorithm

### What is MinMax?

The **MinMax Algorithm** is a recursive decision-making algorithm used in game theory and artificial intelligence. It's designed to find the optimal move for a player, assuming that the opponent also plays optimally.

### How It Works

The algorithm works by:

1. **Simulating All Possible Moves**: Starting from the current board state, it explores every possible future move recursively
2. **Evaluating End States**: When it reaches a terminal state (win, lose, or draw), it assigns a score:
   - **+10**: AI wins
   - **-10**: Human wins
   - **0**: Draw

3. **Maximizing/Minimizing**: 
   - **Maximizing Player (AI)**: Chooses the move with the highest score
   - **Minimizing Player (Human)**: Assumes the opponent will choose moves that minimize the AI's score

4. **Backtracking**: The algorithm backtracks through the game tree, propagating scores up to determine the best move at the current state

### Example Visualization

```
Current Board State
     |     |     
  X  |  O  |  X  
_____|_____|_____
     |     |     
  O  |  X  |     
_____|_____|_____
     |     |     
     |     |  O  

AI evaluates all possible moves:
- Position 5: Leads to draw (score: 0)
- Position 7: Leads to win (score: +10) ✓ BEST MOVE
- Position 8: Leads to loss (score: -10)

AI chooses Position 7
```

### Key Characteristics

- **Complete**: Explores all possible game states
- **Optimal**: Always finds the best move
- **Deterministic**: Given the same board state, always chooses the same move
- **Complexity**: O(b^d) where b is branching factor and d is depth

### Real-World Applications

The MinMax algorithm is used in:
- Chess engines
- Checkers and board games
- Two-player zero-sum games
- Decision-making systems
- Game AI development

---

## ✨ Features

### Core Functionality

- 🤖 **Unbeatable AI**: Powered by the MinMax algorithm with perfect play
- 🎮 **Interactive Gameplay**: Smooth, responsive user interface
- 📊 **Live Score Tracking**: Keeps track of wins, losses, and ties across games
- 🎨 **Modern UI/UX**: Beautiful design with smooth animations and transitions
- 📱 **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- ⚡ **Lightning Fast**: Built with Vite for optimal performance
- 🎯 **Strategic Delay**: AI includes a slight thinking delay for better UX

### Technical Features

- **Type-Safe**: Written in TypeScript for enhanced code reliability
- **Component-Based**: Clean, reusable React component architecture
- **Optimized Rendering**: Efficient state management and React hooks
- **Custom Algorithm**: Hand-crafted MinMax implementation
- **Clean Code**: Well-documented and maintainable codebase

---

## 🛠 Technology Stack

### Frontend Framework
- **React 18.2.0** - Modern UI library with hooks
- **TypeScript 5.2.2** - Type-safe JavaScript
- **Vite 5.0.8** - Next-generation frontend tooling

### Styling
- **CSS3** - Custom styling with modern features
- **Bootstrap Icons** - Beautiful icon library
- **Google Fonts** - Poppins & Raleway typography

### Build Tools
- **ESLint** - Code quality and consistency
- **TypeScript Compiler** - Type checking

### Design System
- **Color Palette**:
  - Background: `#040404` (Dark)
  - Primary Accent: `#18d26e` (Green)
  - Hover Color: `#35e888` (Light Green)
  - Text: `#fff` (White)

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v16 or higher)
- **npm** or **yarn**

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/RikamPalkar/TicTacToe.git
cd TicTacToe
```

2. **Install dependencies**
```bash
npm run build
```

The production-ready files will be in the `dist` folder.

## How It Works

The AI uses the **MinMax Algorithm**, a recursive algorithm that:
1. Evaluates all possible game states
2. Assumes the opponent plays optimally
3. Chooses the move that maximizes the AI's chance of winning
4. Makes the game nearly impossible to beat!

## Technologies Used

- **React** - UI framework
- **TypeScript** - Type-safe JavaScript
- **Vite** - Build tool and dev server
- **CSS3** - Styling with modern features

## Author

**Rikam Palkar** - Microsoft MVP

- Website: [rikampalkar.github.io](https://rikampalkar.github.io)
- LinkedIn: [linkedin.com/in/rikampalkar](https://www.linkedin.com/in/rikampalkar/)
- Article: [Step-by-Step Guide on Medium](https://levelup.gitconnected.com/step-by-step-guide-to-develop-tic-tac-toe-ai-with-blazor-b11c194aac6b)

## License

MIT License - feel free to use this project for learning and personal projects!
