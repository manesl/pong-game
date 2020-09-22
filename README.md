# pong-game

Author: Shweta Satyasheel Mane

A game with paddles and ball, players lose if they miss hitting the ball. The game is displayed on PC using VGA port and paddles are controlled using tactile switches. Debouncing effect of switches is reduced using appropriate software delays.

Files:

* hv_sync.v: generates vga signals for drawing ball, paddle, and changing it shape.
* main.v: core logic to bounce the ball if it hits the paddle, the paddle is moved with switches on the board, and end the game if the ball does not touch the paddle.
* Master.xdc: the master xdc file contains the blocks that will be initialized like VGA port and buttons on the FPGA board. This file is provided by digilent website.
