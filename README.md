# Tic-Tac-Toe AI Agent

This project is an AI-powered Tic-Tac-Toe game developed in Python. The AI agent is capable of playing using **four different algorithms**, providing a challenging opponent that can adapt to various strategies. The goal of this project is to explore different AI techniques for solving classic board games and compare their performance and decision-making processes.

## Features

- **Minimax Algorithm**: A basic AI that evaluates all possible moves to ensure the best outcome.
- **Alpha-Beta Pruning**: An optimized version of Minimax that reduces the number of nodes evaluated, making it faster.
- **Heuristic-based Minimax**: Adds heuristics to the standard Minimax for quicker decision-making without evaluating every possible move.
- **Custom Strategy**: A special strategy to add variety and new challenges to the game.

## Getting Started

### Prerequisites

- **Python 3**
- Required libraries:
  ```bash
  pip install tkinter
  ```
  -OR on arch-
  ```bash
  pacman -S tk
  ```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/3ab3z2/Tic-tac-toe.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Tic-tac-toe
   ```

3. Run the game:
   ```bash
   python Trial.py
   ```

## Usage

- On launching the game, you will be able to select which algorithm the AI will use to play against you.
- The game will display the Tic-Tac-Toe grid, where you can play as 'O' while the AI plays as 'X'.
- Try different algorithms and compare how the AI behaves!

## Algorithms

1. **Minimax Algorithm**  
   The AI evaluates all possible moves and picks the optimal one to either win or force a draw.

2. **Alpha-Beta Pruning**  
   A more efficient version of Minimax, which cuts off branches that don't need to be evaluated, speeding up the decision-making process.

3. **Heuristic-based Minimax**  
   Introduces heuristics to guide the AI in making faster decisions, especially useful for larger game boards or when limited computational resources are available.

4. **Custom Strategy**  
   A unique twist that introduces more variability and challenges to the gameplay. Test it out to see how it differs from the other strategies.

## Screenshots

![image](https://github.com/user-attachments/assets/2fbbe67f-f7df-41c6-803f-f815859eb49d)
![image](https://github.com/user-attachments/assets/bfb223c3-4bfb-4534-9e07-778a36e4f443)
![image](https://github.com/user-attachments/assets/6ea4ce85-2991-4967-9799-3a213b7c7ed1)
![Screenshot from 2024-10-24 23 15 18](https://github.com/user-attachments/assets/1f0d97bc-220f-4785-bdf8-83d5607c5aaf)


## Contributing

Feel free to contribute to this project by forking the repository and submitting pull requests. Contributions can include improvements to the algorithms, bug fixes, or adding new features to the game.

## License

This project is licensed under the GPL License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, feedback, or collaboration ideas, feel free to reach out!

- **GitHub**: [3ab3z2](https://github.com/3ab3z2)

---

Enjoy playing Tic-Tac-Toe with AI! 🎮
