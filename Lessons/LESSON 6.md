##Lesson 6

###Introduction
In this lesson we complete the game by finishing the in-game reset to allow a new game to be easily started when a game ends. This lesson is fairly short to allow time to compete with theirt Fla-Pi Bird games at the end.

###Learning Objectives
Understand how a new game state can be initiated following the end of the previous game.

###Learning Outcomes

#####All students are able to
Implement an in-game reset.  
  
###Lesson Summary
In this lesson we need to add three small peices of code to allow the game to be restarted and the background to change appropriately.  

###Starter
Students should load up their Sounds.sb file from last lesson and test it to make sure everything is working as it should.  

###Main Development
####Fla-Pi Code  
We will add a small piece of new code to the Fla-Pi sprite that hides the bird and returns it to its start position when it receives the message ```reset```  
![Bird Reset](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/6%20In%20Game%20Reset/6.1%20Bird%20Code.jpg?raw=true)  
  
####Stage Code  
We now need to give the stage some instructions as to what background should be displayed at various points in the game. The next piece of code waits until it receives the mesSAGE ```GameOver``` and then waits 3 seconds for previosu code in the game to finish up, it then broadcasts the message ```reset```.  
![Stage Reset Call](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/6%20In%20Game%20Reset/6.1%20Stage%20Code.jpg?raw=true)  
  
The next piece of code is what is actioned when the ```reset``` message is broadcast, it switches the background back to the intro screen and waits for the space bar to be pressed to start a new game. Once this happens, it switches to the ready background for 1 second, then switches to the in game background before resetting the delay to allow pipes to travel across the screen.  
![Stage Reset function](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/6%20In%20Game%20Reset/6.2%20Stage%20Code.jpg?raw=true)  
  
The game should now be saved as Fla-Pi Bird.sb and now the game is finished.  
  
###Plenary  
What is the highest scores that students can score in Fla-Pi bird?
