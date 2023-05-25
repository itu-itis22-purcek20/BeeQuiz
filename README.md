# BeeQuiz

This is a simple text-based Python quiz game. It allows users to answer questions from different categories and difficulty levels. User's progress is saved and displayed in a visual and statistical manner.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data Storage](#data-storage)
- [Future Improvements](#future-improvements)
- [License](#license)

## Features
- Different categories of quiz topics
- Multiple difficulty levels
- Time constraint for each question
- Persistent user data across different sessions
- User statistics, showing total games played, highest and average scores, and total questions answered correctly
- A leaderboard showing the highest scores across all users
- Charts displaying top scores and total questions answered by users
- Calculation of time spent on each question

## Getting Started

### Requirements

To run this program, you need Python 3.5 or later. The only third-party library used is `matplotlib`, which can be installed using pip:
```
pip install matplotlib
```
### Running the Program

1. Clone this repository or download the script.
2. Run the script using Python:
```
python bee_quiz.py
```
## Usage

The program is an interactive console application.

When you start the program, you will be asked for your username. If you are a new user, you will be welcomed and directed to the main menu. If you are a returning user, the program will greet you with your username and take you to the main menu.

The main menu provides four options:

1. **Start Quiz:** You can choose a category and difficulty level, and then you will be presented with a set of questions. You will have to enter the option number of the correct answer within a certain time limit.

2. **Show Stats:** You can view your own statistics (total games played, highest score, average score, and total number of correctly answered questions), the leaderboard, or the time you spent on each question.

3. **Show Chart:** You can view a bar chart representing the top scores or the total questions answered by all users.

4. **Exit:** This option allows you to exit the program.


## Data Storage

User data is stored in a file named 'user_data.pickle' using Python's pickle module. This data includes the username, scores, answers given, time spent on each question, number of correct answers, and number of incorrect answers.

The data is saved in a dictionary format where the key is the username and the value is a list of games played by the user. Each game is represented as a dictionary storing the details of the game.

## Future Improvements

While the current version of the BeeQuiz is fully functional, there are several potential improvements that could be made:

- Additional question categories and difficulty levels
- A more advanced scoring system that takes into account the difficulty level and answer time
- A graphical user interface (GUI) using a library like tkinter or PyQt
- The option for users to add their own questions
- Multiplayer mode where users can compete against each other in real time
- 
## License

This project is licensed under the terms of the MIT license.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
