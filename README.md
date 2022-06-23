# PongGame
Developed a 2 player Pong Game with Java. 
Unlike other Ping Pong Games this version is only capatible with a two human player participants rather than a human playing against a computer. 
There are two parts to the development of this game. 
First, the visual peice of the game must be developed. Visual peice includes the players, ball, paddles and environment. 
 This is further broken down into these classes: Pong Game main class, Game Frame, Game Panel, Paddle, Ball, and Score Keeper. 
 The second part is developing the functionality of the game. 
 

 Visual Base:
 
 - player 1 and player 2 are representated by rectangular paddles. 
 - The ball is drawn to be a white circle.
 - There is a boundary representing a Pong table 
 - There is a text element showing the score of the game
 - There is a line dividing the game panel in the middle representing a seperation between player 1 and player 2 table sides. 


 Functional Elements:
 
 - Player objects move only on the y-axis. 
 - The ball is able to move in both the x and y-axis. 
 - The ball object should change its direction on the x-axis to the opposite if it overlaps with a player object.
 - The ball object should change its direction on the y axis to the opposite if it moves out of the screen on the y-axis.
 - The ball object’s position and direction should be reset if it moves out of the screen on the x-axis.
 - A player gets a point whenever the ball moves out of the screen on the opposite side.
 - The score keeper (text at the top of frame) is updated whenever a player makes a point. 

An element of difficult does exist with this game. When a player hits the ball with their paddle then the velocity of the ball increases. 

Enjoy the game and may the odds be in your favor. 


Demo: https://user-images.githubusercontent.com/82426331/175427481-4e9b1850-0dff-4bd1-bb47-e34caa32b663.mp4

