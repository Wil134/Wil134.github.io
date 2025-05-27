## Number Guessing Game
```mermaid
flowchart TD;
A([Start]) --> B([Generate Number 1-10])
B --> C([Input Number])
C --> D([Is the input a number?])
D -- No --> C
D -- Yes --> E([Is the number lower or higher?])
F -- Lower --> C
F -- Higher --> C
F -- Correct --> G([End])
```

## Instructions for game
1. Computer Generates Number
2. Human inputs number
3. If the number is not a number, it stays stagnant at number input
4. If it is higher or lower than the correct number, it goes back to asking for a new input
5. If the input is correct, the game ends
