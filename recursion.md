# The Call Stack

* Definition
    - The call stack is a structure used by JavaScript to manage function calls during program definition

* Characteristics
    - Operates like a vertical pile, following a last-in-first-out (LIFO) pattern
    - New items are added on top (pushed), and only the top item can be removed (popped)

* Usage:
    - When a function is called, a new frame is added to the stack
    - When a function returns, its frame is removed from the stack

* Illustration:
    - Visualizing the call stack helps understand how JavaScript manages function calls
    - Example program execution involves pushing frames for each function call and popping them after return

* Practical Implications:
    - JavaScript's single-threaded nature means it processes one command at a time, based on the top frame of the call stack
    - Asynchronous events, like timeouts or user interactions, are handled only when the call stack is empty

* Key Points:
    - Top frame corresponds to the currently executing function
    - Function calls add frames to the stack, and returns remove frames

Understanding the call stack's behaviour is crucial for managing program execution and handling asynchronous events effectively.



# Recursion Basics

- New way to solve complex problems: recursion
- Imagine unpacking nested crates of fruits
- Explore recursion: calling a function within itself

* Recursion vs. Iteration:
    - Recursion: calling a function within itself
    - Iteration: counting through each item in a collection
    - Recursion offers an alternative approach to problem-solving compared to iteration

* Example: gently unpacking crates of fruits
    - Analogous to recursively unpacking nested crates
    - Pseudocode demonstrates the concept
    - Calls a function from within itself, illustrating recursion in action

* Pseudocode Demonstration:
    - Shows how to recursively unpack crates based on their content type
    - Uses the __'dump'__ function to unpack crates containing nested crates or fruits
    - Illustrates how recursion simplifies handling nested structures

* A Note on Language:
    - "Recurse" vs "recur" for clarity
    - Back-formation explanation

* Two Cases:
    - Base case: terminates recursion
    - Recursive case: triggers recursion
    - Critical for problem-solving

* A Recursive Example:
    - Movie Theater Problem: determining row number
    - Base case: no one in front
    - Recursive case: someone in front


Recap:

1. Recursion simplifies complex problems:
    - Recursion offers a powerful tool for solving problems that involve repetitive structures or nested data
    - It allows for a more elegant and concise solution to certain types of problems compared to iterative approaches

2. Understanding base and recursive cases:
    - Recognizing and defining the base case is crucial in recursion
    - The base case determines when the recursion should stop, preventing infinite loops
    - Identifying the recursive case defines when the function should call itself again, progressing towards the base case

3. Preparation for advanced recursion:
    - The basics covered in these notes serve as a foundation for tackling more complex recursive problems
    - Advanced recursion may involve more intricate patterns, multiple base cases, or optimisations to improve efficiency
    - Understanding the fundamentals prepares for delving deeper into recursion and applying it to various scenarios
