##Lesson 5

###Introduction
In this lesson, we will add sound effects to the game.

###Learning Objectives
Students will understand why sound effects are placed where they are in the game.

###Learning Outcomes

#####All students are able to
Add appropriate sound effects to the right parts of the game. 

#####Some students are able to  
Download and import their own sounds and put them in appropriate places in the game.
  
###Lesson Summary
In this lesson students will add provided sound effects to their game for scoring, loss of life, and new game.  
###Starter
Explain to students that sounds in video games play an important part in the whole gaming experience. Play the following sounds and see if pupils can guess what popular video games they are from:  
[Pac Man Sound](https://www.dropbox.com/s/6ebq1znsm7c8ebv/Pacman%20Gameplay.mp3)  
[Mario Jump Sound](https://www.dropbox.com/s/d1u9o0om5avyci4/Super%20Mario%20Bros.%20-%20Jump%20Sound%20Effect.mp3)  
[Sonic Ring Sound](https://www.dropbox.com/s/gf1uaxdpy4uzglp/Sonic%20the%20Hedgehog%20Ring%20Sound%20Effect.mp3)  
[Mario Tube Sound](https://www.dropbox.com/s/jga18jfvmsudp43/Super%20Mario%20Tube%20Sound%20Effect.mp3)  
  

###Main Development
This lesson comprises of adding some provided sounds at specific points in the game to add to the experience. Students may wish to download their own sound effects instead.  

To import sounds for a sprite, click on the sounds tab for that sprite and import the sounds you would like that sprite to be able to access as show below:  
![Import Sounds](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Screenshots/Importing%20Sounds.fw.png?raw=true)  
  
####Fla-Pi Code  
Firstly, sounds need to be added to the bird sprite. We add the sfx_wing to the appropriate code so that the wing flapping noise is played when the up arrow is pressed.  
![Wing Sound](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/5%20Adding%20Sounds/5.1%20Bird%20Code.jpg?raw=true)  
  
Next we need to add code to Fla-Pi for when a pipe is successfully passed and a point is scored, to do this we modify the code previously added to include the sfx_point sound afetr 1 is added to Score:  
![Point Score Sound](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/5%20Adding%20Sounds/5.2%20Bird%20Code.jpg?raw=true)  
  
Lastly for Fla-Pi, we need to add sounds for when the bird hits a pipe and for when it dies, again adding the right sounds to the places in the code previsoulsy used for collision detection:  
![Collision Sounds](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/5%20Adding%20Sounds/5.3%20Bird%20Code.jpg?raw=true)  
  
####Stage Code  
The last sound effect we need to add is the whooshing sound to indicate a new game, this is added to the stage code as shown below:  
![Stage Sound Effect](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/5%20Adding%20Sounds/Background%20Code.JPG?raw=true)  

###Plenary  
* Can students come up with any other stages in the game where sound effects could be added?  
* What kind of sounds would they add?
