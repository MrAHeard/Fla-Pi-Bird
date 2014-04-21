##Lesson 4

###Introduction
In this lesson, students will implement code that actions lose conditions, or "Game Over", this includes detecting if Fla-Pi has collided with a pipe or if Fla-Pi has hit the edge of the stage. Code will also be included to allow the game to be restarted in-game without having to keep pressing the green flag.

###Learning Objectives
The main objective of this lesson is to deal with loss conditions in the game.

###Learning Outcomes

#####All students are able to
Implement loss conditions to produce a Game Over state in the game.  
#####Most students are able to
Make suitable predictions about what the code will do. 

###Lesson Summary
Loss conditions are important in any competitive game, they allow the game to end and suitably be restarted without the need to close and reload the game. In Scratch, when we want a new game, rather than having to press the green flag, it would be great if we could handle this in-game to code a reset facility to allow us to start a new game with very little effort. In completing this lesson, we create and maintain a "Game Over" state.

###Starter
Show students the following video, ask them to consider what counts as a loss in the game, if they have played the game, ask them what happens when a game ends? Do they close the app and restart or can they start a new game easily?  
[Flappy Bird Video](https://www.dropbox.com/s/bvcj17e3o8qunm9/Flappy%20Lesson%204%20Starter.mp4)  
  
###Main Development
####Fla-Pi Code  
Firstly, as always we will look at the code for Fla-Pi, this time we are going to modify one existing code block and we are going to add two new sections. The piece of code with the green flag nees a quick addition, here we are going to change it so that the bird points in the right direction when the game starts.  
![Fla-Pi Direction](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/4%20Lose%20Conditions/4.2%20Bird%20Code.jpg?raw=true)  
  
Now we are going to add the first of our two new code blocks for the bird, the code below is the code that checks throughout the game if the bird is touching the pipe or touching the edge of the stage. If the bird is touching the pipe, the bird points downwards after colliding and continues to travel down the screen until it is at the bottom. This script then broadcasts the ```Game Over``` message which we will deal with shortly. It then hides the bird and waits 3 seconds. The reason it waits is to allow time for the Game Over script to perform its actions and it stops the bird colliding with further pipes that may come along.  

If the bird is touching the edge of the screen it is forced to point downwards once more and a Game Over message is broadcast.  
![Collision Detection](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/4%20Lose%20Conditions/4.1%20Bird%20Code.jpg?raw=true)  
  
The last piece of Fla-Pi code we need to implement in this lesson is that of what Fla-Pi should do in the event of "Game Over", the code below waits, retruns Fla-Pi to the start position, hides and then stops the script.  
![Fla-Pi Game Over](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/4%20Lose%20Conditions/4.3%20Bird%20Code.jpg?raw=true)  
  
####Pipe Code  
Now after selecting the Pipe sprite we are going to add one new script that deals with the Game Over scenario to stop the nextpipe command being called. By adding the code below we set the variable 1 to 0 and hide the pipe, this causes the nextpipe command to stop the whole script until it is specifically called again.  
![Pipe Game Over](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/4%20Lose%20Conditions/4.1%20Pipe%20Code.jpg?raw=true)  
  
####Game Over Code  
Now we need to add some code to the Game Over sprite to tell it to show when the game is in a state of Game Over. The code for this shows the graphic, waits a second and hides then stops the script.  
![Game Over Code](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/4%20Lose%20Conditions/4.1%20Game%20Over.jpg?raw=true)  
  
###Plenary
Students should predict what effect the following modifications would have on the game:  
* Not having a 1 second wait in the Game Over script they added.
* Not changing the delay to 0 when in the pipe code.
* Not brodcasting GameOver in the Fla-Pi code.  
  
