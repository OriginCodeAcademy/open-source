# Hangman UI

Most people are probably familiar with the game of Hangman. The first player picks a word or phrase, and the second player has to guess it a letter at a time. If they make six wrong guesses (i.e. the target word does not contain the guessed letter), they lose. If they guess the entire word before then, they win.

This afternoon the objective is to make a Hangman guessing player in JavaScript. The web application should proceed as follows:

## Rules
- There must be three components of the user interface:
  - Introduction: A page to explain the game with a link to the interface
  - Interface: A page to play the game
  - Result: A page of results that shows the answer and whether the user won or lost

### Level 1
The first level should consist of an initial scaffolding of the web application. At this point, the application should have the three required pages connected and a design for the application.

### Level 2:
The second level consists of the main logic and mechanics of the hangman game and a working version of the interface. At this point, it should also tell the user whether they guessed right or wrong.

### Level 3:
The third level will replace a hard-coded set of answers with random words from an API of your choosing. A user should be able to select a difficulty for each word.

### Level 4:
The fourth level will implement a feature that will give a hint if a user is stuck, by sacrificing a body part.

### Level 5:
The last level consists of creating a scoreboard to keep track of the time and score of a user after completing the game.

## Conclusion
The specification is otherwise open-ended to allow you to focus on whatever part of the problem interests you. For example:

* You may choose the form of user interface (e.g. React, Vanilla JS).

* You can either show only the number of wrong guesses made, or actually draw the hangman using ASCII art.
