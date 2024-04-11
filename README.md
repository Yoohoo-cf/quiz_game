# Quiz Game Project

Welcome to the Quiz Game Project! This interactive Python application runs a command-line based quiz game that presents a series of questions to the user and keeps track of the score. It's a great way to test your knowledge on various topics!

## Project Overview

The Quiz Game is written in Python and utilizes object-oriented programming principles. It consists of several components that work together to manage the quiz flow, question retrieval, and score tracking.

## How It Works

The game initializes by creating a pool of questions from a pre-defined set of data. Each question is presented one by one until the user has answered all of them. After the last question, the game reports the user's final score.

## Files in the Project

- `question_model.py`: Defines the `Question` class that is responsible for creating question objects with text and answer attributes.
- `data.py`: Contains the `question_data` list of dictionaries, where each dictionary represents a question and its corresponding answer.
- `quiz_brain.py`: Contains the `QuizBrain` class which manages the quiz logic, such as displaying questions, checking answers, and keeping score.
- `main.py`: The entry point of the application, setting up the question bank and the quiz game loop.

## Usage

To play the quiz game, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone the repository to your local machine:
   ```
   https://github.com/Yoohoo-cf/quiz_game
   cd quiz-game
   ```
3. Run the script using Python:
   ```python3 main.py```

4. Answer the interactive questions in the command line by typing your answers and pressing Enter.

## Customizing the Questions

You can customize the questions by modifying the `question_data` in `data.py`. Add new questions or edit existing ones to create your own quiz.

## Contributing

Contributions to improve the game or enhance its features are welcome. Feel free to fork the repository, make your changes, and create a pull request with your improvements.

## License

This project is licensed under the MIT License.


Enjoy testing your knowledge with the Quiz Game Project!
