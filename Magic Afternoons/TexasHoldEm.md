# Texas Hold Em

## The Problem
You are a contractor for the World Series of Poker (WSOP) cable network.

The play-by-play announcers have asked if it's possible to know what hand the players are holding and which hand won the round.

Since this is live TV - they need these answers quick!

The producer has asked you to solve this problem.

## Your Task

Write a NodeJS script to read in a text file describing the final hands after a round of poker, figure out which hand won, and output the winner in the terminal.

## Example Input/Output

### Input
Each card is a pair of characters. The first character represents the face, the second is the suit. Cards are separated by exactly one space.

`Kc` - King of Clubs
`9s` - Nine of Spades
`Th` - Ten of Hearts (T represents 10)
`Ad` - Three of Diamonds

Each players hands are presented on their own line.

```
Kc 9s Ks Kd 9d 3c 6d
9c Ah Ks Kd 9d 3c 6d
Ac Qc Ks Kd 9d 3c
9h 5s
4d 2d Ks Kd 9d 3c 6d
7s Ts Ks Kd 9d
```

### Output
```
Kc 9s Ks Kd 9d 3c 6d Full House (winner)
9c Ah Ks Kd 9d 3c 6d Two Pair
Ac Qc Ks Kd 9d 3c 
9h 5s 
4d 2d Ks Kd 9d 3c 6d Flush
7s Ts Ks Kd 9d 
```

## High Level Overview

- [ ] Create a new folder on one of your teammates devices.
- [ ] Create a new text file within this folder named `cards.txt`.
- [ ] Run `npm init` and `git init` to initialize the project.
- [ ] Create an `index.js` file to house your code.
- [ ] Work on the solution inside of `index.js`.
- [ ] Push your solution to GitHub (Fork the project if your GitHub wasn't used)

## Extra
- Can you rearrange the cards to make it super clear to the announcers which hand won?
