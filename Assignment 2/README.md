How it Works:

Capturing Input: The input() function pauses the program and waits for the user to type something. Whatever they type is stored as a string in the variable user_input
.
Initializing Counters: We start two variables, letters and digits, at 0. These act as "scoreboards" that we’ll update as we scan the text.

The Scanning Loop:
The for char in user_input: line looks at every single character one by one (including spaces and symbols like !).

Condition 1 (isalpha): If the character is a letter (A-Z), the letters count goes up by 1.

Condition 2 (isdigit): If it's a number (0-9), the digits count goes up by 1.

Other Characters: If it's a space or a symbol, the program simply ignores it and moves to the next character.

Displaying Results: Finally, it prints the totals using f-strings (f"..."), which allow us to plug our variables directly into the output text to match the required form

Features:

Dynamic Input: Handles any string entered by the user.

Filtering: Ignores spaces and special characters/punctuation.

Standardized Output: Displays results in a clear KEY VALUE format.