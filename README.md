These three Python codes implement variations of an AI guessing game where the player thinks of a number between 1 and 100, and the AI tries to guess it based on the player's feedback. The three strategies used in the code are:

1. **Randomized BFS (Breadth-First Search) Approach**:
   - The AI guesses numbers using a randomized breadth-first search method.
   - It starts with a list of all possible numbers (from 1 to 100) and makes a random guess from this list.
   - Based on the player's feedback ('h' for too high, 'l' for too low, 'c' for correct), the AI reduces the list of possibilities by eliminating numbers that are too high or too low. It continues until it guesses correctly or runs out of attempts (10 attempts max).

2. **Randomized DFS (Depth-First Search) Approach**:
   - Similar to the BFS version but uses a DFS-like strategy.
   - The AI maintains a stack of possible numbers and makes a random guess from the stack.
   - After each guess, the AI adjusts the stack by removing numbers based on the player's feedback ('h', 'l', or 'c'). The process continues until it either guesses the correct number or reaches the maximum number of attempts.

3. **Random Walk Approach**:
   - In this version, the AI performs a "random walk" through the possible guesses, randomly selecting numbers from the set of possibilities.
   - It continually updates the set of possible numbers based on the player's feedback ('h', 'l', or 'c') and repeats the process until it guesses the correct number or exceeds the maximum of 10 attempts.
