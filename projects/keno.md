---
layout: project
type: project
image: img/keno.png
title: "Keno"
date: 2022
published: true
labels:
  - Java
  - Game
summary: "Keno betting game utilizing Java Swing."
---
### introduction
This Java application is designed to simulate a Keno game, offering a practical demonstration of Swing’s capabilities for building interactive GUIs. 
Keno is a lottery-style game where players select numbers and wait for a draw to see if their choices match the drawn numbers. This was a project created for ICS211.

### start of the game
![k3](https://github.com/user-attachments/assets/5f9a856a-ccbf-40e5-9a3f-acab5ac4a77b)

### choose 10 numbers and place a bet
![k4](https://github.com/user-attachments/assets/d53d6220-47f1-4109-bcd2-131f4c4d2f65)

### press play to see the computer's choices and see your hits
![k5](https://github.com/user-attachments/assets/38133659-7ffa-481d-b8b1-eb5edb75cca5)


### features
The application features a GUI built with Java Swing, showcasing various Swing components such as buttons, labels, and panels. Players can select a set of numbers from a range, place a bet from a given amount of in-game currency, and initiate a draw in which the computer will randomly select a subset of numbers to simulate the Keno drawing process. The application provides visual feedback by displaying the selected numbers, the drawn numbers, the results of the game, and it's subsequent payouts in real-time, while recording the game onto a .txt file. The game can also be repeated as many times as the user wants until they want to end.

```
Key functionalities:
- Number Selection: Users can choose their preferred numbers through a series of checkboxes or buttons.
- Draw Mechanism: A button triggers the random generation of winning numbers, utilizing Java’s Random class for number generation.
- Results Display: The application updates the interface to show the drawn numbers and highlight matches.
- User Interaction: Swing components such as JButton, JLabel, and JPanel are used to create an intuitive and responsive user experience.
```

This project illustrates the practical application of Java Swing for developing interactive desktop applications and demonstrates core programming concepts such as event handling, random number generation, and dynamic UI updates.


![k2](https://github.com/user-attachments/assets/0de50d0a-0d97-49ce-87a2-632ddad959d4)
