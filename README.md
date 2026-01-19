# Hangman-Game
A classic implementation of the Hangman game developed in C++. This project demonstrates a clear separation of concerns by utilizing modular programming techniques, including custom header files and multiple source files.

🛠 Technical Highlights
1) Modular Architecture: Organized into main.cpp, hangman_functions.cpp, and hangman_functions.h to ensure maintainability and clean code structure.

2) Data Structures: Utilizes std::vector for dynamic storage of incorrect guesses and std::string for codeword manipulation.

3) Game Logic Engine: * Input Validation: Iterates through codewords to match character guesses.

4) State Management: Tracks "misses" to dynamically render the hangman ASCII art.

5) Conditional Rendering: Features a multi-stage visual progression based on user errors.

6) Header Guarding: Demonstrates professional C++ practices by declaring function prototypes in a header file to be shared across the project.

🎮 How to Play
1) Greeting: The game starts with a welcome message and instructions.

2) The Goal: Guess the hidden codeword ("codingcleverly") one letter at a time.

3) Visual Feedback:

    a. Correct Guesses: Fill in the blanks in the codeword display.

    b. Incorrect Guesses: Added to a "misses" list, triggering a new part of the hangman drawing.

 4) Win/Loss: You win if you complete the word before 7 misses. If the hangman is fully drawn, the game ends.
