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
