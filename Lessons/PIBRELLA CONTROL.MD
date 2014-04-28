#Control Fla-Pi Bird witha Pibrella

##Code changes
To control Fla-Pi Bird using the lovely big red button on a Pibrella, simply change the two pieces of code in the Fla-Pi Bird sprite to the following (this is using Scratch GPIO5):  
![Pibrella Control](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/7%20Pibrella/Code%20Changes%20Fla-Pi%20Bird%20Brella.fw.png?raw=true)  
  
Create a variable called AddOn and at the start of the game ```set AddOn to Pibrella``` then simply change the ```if up arrow pressed``` to ```if switch sesnor value = on``` to change the input.
