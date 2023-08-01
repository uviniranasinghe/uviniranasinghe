# Pre Hack Eligible Quiz Game

This is a simple C programming language quiz game designed to assess the basic knowledge of teams. The quiz consists of 10 multiple-choice questions related to C programming, and teams need to answer them. After completing the quiz, the team's score and eligibility status for the hackathon will be displayed. To be eligible for the hackathon, a team must score at least 80%.

## Instructions

1. The program allows you to create multiple teams to participate in the quiz.
2. Each team will be asked a set of 10 questions, and they need to answer them correctly.
3. The quiz is multiple-choice, and the team has to select one of the options (A, B, C, or D) as their answer for each question.
4. After answering all the questions, the team's score will be calculated and displayed.
5. If the team's score is at least 80%, they will be eligible for the hackathon.
6. The program can handle a maximum of 50 teams.

## Quiz Questions

The quiz questions are defined in the code and include questions related to C programming. Each question has four options, and one of them is the correct answer.

## How to Use

1. When the program is executed, a menu will be displayed with the following options:
   - `S`: Start the quiz for a new team.
   - `V`: View the records of all teams along with their scores and eligibility status.
   - `H`: View the help instructions.
   - `Q`: Quit the program.

2. To start the quiz for a new team:
   - Choose the `S` option from the menu.
   - Enter the team name when prompted.
   - Answer the 10 multiple-choice questions one by one by typing the corresponding option letter (A, B, C, or D).

3. After answering all the questions, the team's score and eligibility status will be displayed.

4. To view the records of all teams:
   - Choose the `V` option from the menu.

5. To view the help instructions:
   - Choose the `H` option from the menu.

6. To quit the program:
   - Choose the `Q` option from the menu.

## Score Calculation

The team's score is calculated as the percentage of correct answers out of the total number of questions attempted.

## Eligibility Criteria

To be eligible for the hackathon, a team must score at least 80%.

## Compilation

To compile and run the code, ensure you have a C compiler installed on your system. You can compile the code using a C compiler such as GCC:

```
gcc quiz.c -o quiz
./quiz
```

Note: The above commands assume that the code is saved in a file named `quiz.c`.

## Contributions

This program is a simple demonstration of a quiz game and can be expanded or modified for other purposes. Contributions and improvements are welcome.

## Authors

This code was written by [Your Name].

## License

This project is licensed under the [Your License].
