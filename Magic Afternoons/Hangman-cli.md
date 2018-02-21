# Hangman CLI

Most people are probably familiar with the game of Hangman. The first player picks a word or phrase, and the second player has to guess it a letter at a time. If they make six wrong guesses (i.e. the target word does not contain the guessed letter), they lose. If they guess the entire word before then, they win.

This quiz is to make a Hangman guessing player in JavaScript. Play should proceed as follows:

```
1. The program requests a word or phrase pattern, e.g. "-------".

2. The program suggests a letter, or may guess the entire word or phrase.

3. The user indicates which letter positions, if any, match that letter.
   If none match, a life is lost. If six (or configurable) lives are lost,
   the program loses.
```

The specification is otherwise open-ended to allow you to focus on whatever part of the problem interests you. For example:

* You may choose the form of user interface (e.g. Command line input via Repl.it or web based input using jQuery via CodePen).

* You can either show only the number of wrong guesses made, or actually draw the hangman using ASCII art.

* You may concentrate on improving the play, for example by using a dictionary to improve the guesses made at each stage. All Macs have a file containing a large list of words, which you can view by running `nano /usr/share/dict/words` in the command line.
