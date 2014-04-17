##Lesson 1

###Introduction
In this lesson, students will start to get the graphics moving on screen. At this stage there will be no scoring of points, dying or interaction between sprites, this session simply gets the bird moving up and down, and the pipe moving across the screen. The assumption is made that students undertaking this task are already familiar with Scratch in terms of creating variables and broadcasting messages within the game, If this is not the case, this will need to be considered before starting development.

###Learning Objectives
The objective of this lesson is to understand what code needs to be added to the game in order for the sprites to move the way they need to in Fla-Pi Bird.

###Learning Outcomes

#####All Students Are Able To
Get the bird and the pipe moving the way illustrated.
#####Most Students Are Able To
Change the values so that the bird and the pipe move more quickly.

###Lesson Summary
The lesson will begin with a small discussion on copyright and plagiarism to ensure students understand the importance of crediting original sources when using it for their own purposes.Students will then begin to code a game in Scratch. The code illustrated in this lesson will allow students to successfully get sprites moving on the screen in the direction they need them to in order to fulfil the game.
###Starter
Place the word copyright on the board to provoke a discussion on what copyright is and what the implications of it are. You could then explain that cloning games has become commonplace due to the intricate nature of software law. You only need to look on the appstore for many different versions of seemingly the same game. Highlight that we are going to clone a well-known game, however they students should be aware of the laws around copyright and the consequences of plagiarising someone else’s work and simply passing it off as their creation. The original Flappy Bird game was written by Dong Nguyen and credit must go to him for providing the inspiration and motivation to reproduce a working clone to get students thinking computationally.
###Main Development
* Students will begin by opening scratch and deleting the cat sprite by right clicking on it and choosing delete.
* They will then choose new sprite and import both costumes for the Fla-Pi Bird. These can be found below:  
* Here is how to import graphics.  
![Imprt Graphic](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Screenshots/Import%20Graphic%20Screen%20Shot.fw.png?raw=true)  
  
![Flap-Pi Bird Costume 1](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Flappy.fw.png?raw=true)  
  
![Fla-Pi Bird Costume 2](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Flappy2.fw.png?raw=true)  

* Students will then import the 3 different costumes from the stage in the same way, these can be found below:  

![Game Intro Screen](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Background.png?raw=true)  
![Ready Screen](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Ready.fw.png?raw=true)  
![Game Background](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Background.png?raw=true)  

* Next, the graphics for the pipes should be imported, there are nine of these, ensure students import all of these costumes for their pipe sprite.  

![Pipe 1](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe1.png?raw=true) Pipe 1  
![Pipe 2](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe2.png?raw=true) Pipe 2  
![Pipe 3](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe3.png?raw=true) Pipe 3  
![Pipe 4](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe4.png?raw=true) Pipe 4  
![Pipe 5](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe5.png?raw=true) Pipe 5  
![Pipe 6](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe6.png?raw=true) Pipe 6  
![Pipe 7](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe7.png?raw=true) Pipe 7  
![Pipe 8](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe8.png?raw=true) Pipe 8  
![Pipe 9](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe9.png?raw=true) Pipe 9  

* Finally, the 'Game Over' graphic should be imported.  
![Game Over](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/GameOver.fw.png?raw=true)  

* Ok, so that’s the graphics in place, now we need to add some code to the individual elements so that they show at the right time at this very early stage of the game. At this stage, the bird and the pipe do not require any code, first we will look at the code to add to the Game Over sprite, make sure the game over sprite is selected:  
![Game over code](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/1%20Graphics/Game%20Over%20Code.JPG?raw=true)  
The code above hides the game over graphic when the game starts, this graphic will be used later on and sdisplayed when a game ends.  
* The code for the stage (background) now needs to be added. Here, the code switches to the game intro screen when the game starts. Then the game waits for the space key to be pressed to start the game, when pressed, the game waits 1 second, and then broadcasts a message called start, at this point the background is switched to the playing background. This concludes this lesson.  
![Stage code](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/1%20Graphics/Stage%20Code.JPG?raw=true)  
* Students should save the file as ```Fla-Pi Graphics.sb```   
###Main Development
Students should be made aware once again of the importance of ethical responsibilities when writing software to avoid potential consequences.  
  
