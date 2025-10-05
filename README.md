# DSA_Assignmnet1
This repository contains solutions to three DSA assignment problems implemented in C++ using object-oriented programming. Each problem is modular (.cpp and .h files) and hides internal implementation details.

The header files (.h files) for all tasks were provided by the professor. Only the implementation files (.cpp files) are uploaded in the repository.

Link to repository https://github.com/Noorsabaa/DSA_Assignmnet1

 Problem Summaries

1. Polynomial ADT

Built using a linked-list–like design with supporting functions in .cpp files.

Provides operations such as insertion, printing, addition, multiplication, and differentiation.

Automatically merges terms with the same exponent and removes zero coefficients.

Includes safeguards for negative values and prevents overflow in arithmetic operations.

2. Text Editor Simulation

Implements a text editor using two stacks to manage characters on the left and right of the cursor.

Supports inserting, deleting, and moving the cursor efficiently.

Displays the text with the cursor position clearly.

Handles invalid inputs and prevents moving the cursor beyond text limits.

3. UNO Card Game Simulation

Simulates a simplified UNO game for 2–4 players with a 76-card deck (without wild cards).

Uses linked lists for the deck and discard pile, and stacks for player hands.

Implements card effects like Skip, Reverse, and Draw Two with proper game logic.

Handles deck shuffling, turn order, and ending conditions (win or no cards left).


 Challenges and Learnings
1. Encapsulation Limits

The provided header files couldn’t be edited, so internal variables had to be managed within the .cpp files.
This required careful design using helper functions, maps, and linked structures to maintain abstraction and separation.

2. Polynomial ADT Issues

Managing duplicate exponents, zero coefficients, and negative values needed precision in all operations.
Differentiation and multiplication also required overflow checks to prevent errors.

3. Text Editor Behavior

Keeping track of the cursor during insertion and deletion was challenging.
Boundary conditions (like deleting at the start or inserting invalid characters) were handled safely to ensure smooth performance.

4. UNO Game Logic

Getting the turn order, special card actions, and 2-player reverse rules right required multiple test runs.
The game also needed to handle empty decks and cases where no player could make a valid move.
