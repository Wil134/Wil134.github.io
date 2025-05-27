```mermaid
flowchart TD;
Start([Start]) --> Generate Random Number([Generate a Random Number])
Generate Random Number([Generate Random Number]) --> User Inputs Number([User Inputs Number])
User Inputs Number([User Inputs Number]) --> Is the input a number?([Is the input a number?])
Is the input a number?([Is the input a number?]) -- No --> User Inputs Number([User Inputs Number])
Is the input a number?[(Is the input a number?)] -- Yes --> Is the input correct?([Is the input correct])
Is the input correct?([Is the input correct]) -- Too high --> Input too high([Input too high])
Is the input correct?([Is the input correct]) -- Too Low --> Input too low([Input too low])
Is the input correct?([Is the input correct]) -- Correct --> Congratulations!([Congratulations!])
Congratulations!([Congratulations!]) --> End([End])
```
