## Number Guessing Game
```mermaid
flowchart TD;
A([Start]) --> B([Generate Random Number])
B --> C([Input Number])
C --> D([Is the input a number?])
D -- No --> C
D -- Yes --> E([Is the number correct?])
E -- No --> D
E -- Yes --> ([(Congratulations!])
F --> G([End])
```

## Instructions for game
1. Computer Generates Number
2. Human inputs number
3. If the number is not a number, it stays stagnant at number input
4. If it is a number, and correct, you win
