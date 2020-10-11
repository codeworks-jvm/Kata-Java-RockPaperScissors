# Kata-Java-RockPaperScissors
This kata is inspired by the common rock-paper-scissors-lizard-spock game.

## Instructions
You have to implement a rock-paper-scissors solver with TDD.
Each step will add a new sign, for each step you have to create all tests for the new rules then modify the solver to pass the tests.

The function takes in parameters the two sign select by each player. The function may return the winner sign or "draw" if no one wins.
The solver must not be case-sensitive.

# Rules & examples
* Step 1 : Rock and Paper
  - The paper prevails against the rock.
* Step 2 : Scissors
  - The scissors prevail against the paper.
  - The rock prevails against the scissors.
* Step 3 : Lizard
  - The lizard prevails against the paper.
  - The scissors prevail against the lizard.
  - The rock prevails against the lizard.
* Step 4 : Spock
  - Spock prevails against the scissors.
  - Spock prevails against the rock.
  - The lizard prevails against Spock.
  - The paper prevails against Spock.
  
Examples :
  - rockPaperScissors("rock", "paper") must return "paper"
  - rockPaperScissors("rock", "rock") must return "draw"
  
## Code
In the `src/main/java` folder, you will find the class `App` with the function ready to be implemented.
In the `src/test/java` folder, you will find the class `AppTest` with the first test ready to be implemented.

## Test it
You can use `mvn test` to test your code. If all tests pass, you can go to the next rule !

But first install the dependencies with `mvn clean install -DskipTests`. Thanks.

## Optimisation & clean code
When you add a rule try to keep you code clean and easy to read. You have to clean your code each time you had a new rule.