---
layout: project
type: project
image: img/rps.jpg
title: "Rock Paper Scissors"
date: 2023
published: true
labels:
  - C
  - Command-line
  - Game
summary: "A simple rock paper scissors game"
---

![Screenshot 2024-09-05 111501](https://github.com/user-attachments/assets/178748d4-9c76-4f50-b83b-f1bfb2b47eec)

This game was originally going to be made in Java with Swing but I already had a significant project utilizing Swing, so I wanted to test my knowledge in C by making this simple command-line game. This project deepened my knowledge in the language after only learning C for a semester and got me more comfortable with the differing syntax from java.

### key features
This is a simple command-line game in C. 
The user will play against the computer using a random number generator to act as the computer's choice. 
It can be played multiple times in a single session with an option to either keep playing or quit after each match.

The game keeps track of the user's score (Win/ Lose/ Draw).
And at the end of the session, the program will print the final scores and a small print thanking the user for playing.

The game also has two input buffers where it will only read the first character of the input to take into the count some input errors such as misreading the instruction by typing the full words or misspelling.
So only the first character will be read. 

```
<-------RULES----------->
* PAPER beats ROCK
* ROCK beats SCISSORS 
* SCISSORS beats PAPER
* duplicate hands = draw
<----------------------->
```
### excerpt from one session:
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
