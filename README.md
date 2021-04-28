# Minesweeper

## About
You played this game when the Internet cut off, didn’t you? It is time to remember the good old days. In this project, you will create your own "Minesweeper" game.

## Learning outcomes
This project will teach you how to work with multidimensional arrays in Java. You will be dealing with algorithms for generating the playfield and processing player moves. You will also find out what collections and stacks are.

## Stage 1: Lay down the groundwork
### Description
Minesweeper is a game of logic where the player is presented with a field full of hidden mines. The goal is to mark the positions of all mines without setting any of them off. It's not a game of wild guessing: it offers hints showing the number of mines around each cell. One wrong move, and game over!

### Objective
Your first step is easy: you need to output some state of the minefield.

Set the minefield size and place any number of mines you want on it. At this point, all the mines are there in plain sight – we are not going to hide them from the player just yet.

You can use any character you want to represent mines and safe cells at this step. Later on, we will use X for mines and . for safe cells.

## Stage 2: Flexible mines
### Description
It's no fun when the field has the same setup every time and you know where all the mines are located. Let's generate a random configuration every time the player wants to play the game.

To improve the program, we need to let the player choose how many mines they want on the field. The player needs to input the number of mines they want with their keyboard.

### Objectives
Your program should ask the player to define the number of mines to add to a 9x9 field with the message "How many mines do you want on the field?". It should then use the input to initialize the field and display it with the mines. At this point, the mines are still visible to the player; you will hide them later.

Make sure to use the following marking symbols:
  → X for mines
  → . for safe cells 
