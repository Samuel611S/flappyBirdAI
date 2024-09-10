# FlappyBirdAI

A simple AI-driven version of the classic Flappy Bird game built using Python and machine learning algorithms. The AI is trained using reinforcement learning to play the game on its own.

## Features

- **Flappy Bird gameplay**: Classic Flappy Bird mechanics with a simple 2D interface.
- **AI Agent**: Utilizes a neural network to learn and improve its gameplay over time.
- **Training Mode**: The AI uses Q-learning or other reinforcement learning techniques to train itself to play the game.
- **Real-time visualization**: See how the AI learns from trial and error during gameplay.
- **User vs AI Mode**: Play the game yourself or watch the AI in action.

## Installation

### Requirements

Make sure you have the following installed:

- Python 3.x
- `pygame` for the game interface
- `neat`

You can install the required packages using `pip`.

### Clone the Repository

Clone the repository and navigate to the project directory.

## Usage

### Running the Game

You can start the game by running the `flappybird.py` script.

## How It Works

- The AI is trained using a neural network that makes decisions based on the bird's current position, velocity, and the distance to obstacles.
- The AI receives rewards based on how long it survives and is penalized when it crashes.
- Over time, the AI learns to avoid obstacles by adjusting its flapping behavior.

## File Structure

- `flappybird.py`: The main game file, allowing the user or AI to play.

## Contributing

Contributions are welcome! Please submit a pull request with your changes and ensure the code follows the existing style and structure.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
