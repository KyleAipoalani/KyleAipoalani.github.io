---
layout: project
type: project
image: 
title: "Rock Paper Scissors"
date: 2023
published: true
labels:
  - C
  - command-line game
summary: "A simple rock paper scissors game"
---

## introduction to the game
rock, paper, scissors is a game where two players (preferably in-person) each choose between various hand shapes: rock, paper, and scissors.
Their choices will be simultaneously shown at once, and depending on which hand beats the other, either one player wins or no one wins in a draw. 
```
<-------RULES----------->
* PAPER beats ROCK
* ROCK beats SCISSORS 
* SCISSORS beats PAPER
* duplicate hands = draw
<----------------------->
```
## how the game works
This is a simple command-line game in C. 
The user will play against the computer using a random number generator to act as the computer's choice. 
It can be played multiple times in a single session with an option to either keep playing or quit after each match.

The game keeps track of the user's score (Win/ Lose/ Draw).
And at the end of the session, the program will print the final scores and a small print thanking the user for playing.

The game also has two input buffers where it will only read the first character of the input to take into the count some input errors such as misreading the instruction by typing the full words or misspelling.
So only the first character will be read. 

## excerpt from one session:
```
=========match#1=========
Enter your choice 
(r for Rock, p for Paper, s for Scissors): r

                Player chose: rock
                Computer chose: scissors
                You win!

 Play again? (y/n): 
 note: not typing 'y' or 'yes' will result in a game over
   :y

Scores: Player: 1 | Computer: 0 | Draws: 0

=========match#2=========
Enter your choice 
(r for Rock, p for Paper, s for Scissors): paper

                Player chose: paper
                Computer chose: scissors
                You lose!

 Play again? (y/n): 
 note: not typing 'y' or 'yes' will result in a game over
   :yes

Scores: Player: 1 | Computer: 1 | Draws: 0

=========match#3=========
Enter your choice 
(r for Rock, p for Paper, s for Scissors): knife

  ERROR:
Invalid input. Please enter 'r', 'p', or 's'.

=========match#3=========
Enter your choice 
(r for Rock, p for Paper, s for Scissors): scissos 

                Player chose: scissors
                Computer chose: paper
                You win!

 Play again? (y/n): 
 note: not typing 'y' or 'yes' will result in a game over
   :n

Scores: Player: 2 | Computer: 1 | Draws: 0

=========Final=========
Games played: 3
Player: 2 | Computer: 1 | Draws: 0
Thanks for playing!
```
