##Lesson 3

###Introduction
This lesson introduces variables to the game, two variables are used in the game. Score and Delay. 

###Learning Objectives
Students will understand how variables are implemented in games and how they are reset at the start of each new game.

###Learning Outcomes

#####All students are able to
* Implement a score variable to keep track of the number of pipes Fla-Pi has successfully navigated through.
* Implement a delay variable that will be used later on to stop the pipes travelling across the screen.  
  

###Lesson Summary
Students will create two variables, Score and delay. The score keeps count of pipes that Fla-Pi has successfully travelled through based on the position of the pipe on the screen (still no crash checks at ths stage) and the delay variable will be used in later lessons to stop pipers travelling across the screen when the game is in the game over state.

###Starter
As mentioned earlier in this series, there is an assumption made that students know what a variable is, if they don't it would be beneficial to point out now that a variable is a value in a program that can change depending on actions within the program. Show students the image below and ask them what the different variables are that they can see in the Super Mario World game from looking at the screenshot.  
![Super Mario World Screenshot](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Screenshots/MarioVariables.PNG?raw=true)  
  

###Main Development  
The first thing to do in this lesson is to get students to make two new variables form the Variable section within Scratch. Firstly Score, available for all sprites, and secondly, delay, again available to all sprites.  
  
  
####Fla-Pi Code  
Now the variables have been created, we need to add the relevant bits of code into our game. Firstly, in the piece of Fla-Pi bird code that detects a keypress, straight after the ```When I receive Start``` line, place a block setting the Score to 0, this ensures at the start of every new game the score is zero.  

![Bird Start Position](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/2%20Moving%20Sprites/2.3%20Bird%20Code.jpg?raw=true)  
  

![Bird Costume](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/2%20Moving%20Sprites/2.2%20Bird%20Code.jpg?raw=true)  
  

![Bird Moving Code](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/2%20Moving%20Sprites/2.1%20Bird%20Code.jpg?raw=true)  
  

  
####Pipe Code  

###Plenary
Students 
