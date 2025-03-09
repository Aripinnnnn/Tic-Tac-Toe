# Tic Tac Toe

## Description
Tic Tac Toe is a simple game built using **React** as a learning project to understand the basics of React from the official documentation. This project focuses on key concepts such as components, state management, and event handling in React.

## Features
- Classic 3x3 Tic Tac Toe gameplay.
- Interactive UI with real-time updates.
- Player turn indication.
- History every player turn
- Winning condition detection.
- Restart game functionality.

## Technologies Used
- **React.js** for building the UI.
- **JavaScript (ES6+)** for logic and interactivity.
- **CSS** for basic styling.

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/Aripinnnnn/Tic-Tac-Toe
   cd tic-tac-toe
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. Open `http://localhost:5173` in your browser to play the game.

## Key Learnings
- Understanding React components and props.
- Managing state using `useState`.
- Lifting state up
- Handling events and user interactions.
- Using conditional rendering in React.
- Structuring a React project following best practices.

## Example Code Snippet
```javascript
function Square({ value, onClick }) {
  return (
    <button className="square" onClick={onClick}>
      {value}
    </button>
  );
}
```

## Future Improvements
- Add a history feature to track moves.
- Implement AI opponent.
- Improve UI/UX with animations and better styling.

## Contribution
Feel free to contribute! Fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the **MIT License**.

