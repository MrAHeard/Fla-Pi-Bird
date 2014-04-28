#Control Fla-Pi Bird with a Pibrella

How would you like to now change your code so you can control Fla-Pi Bird with the button on a Pibrella like in the link below?  
[Pibrella controlled Fla-Pi Bird](https://vimeo.com/93175140)  
  

##Code changes
To control Fla-Pi Bird using the lovely big red button on a Pibrella, simply change the two pieces of code in the Fla-Pi Bird sprite to the following (this is using Scratch GPIO5):  
![Pibrella Control](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20Lesson/7%20Pibrella/Code%20Changes%20Fla-Pi%20Bird%20Brella.fw.png?raw=true)  
  
Create a variable called AddOn and at the start of the game ```set AddOn to Pibrella``` then simply change the ```if key up arrow pressed``` to ```if switch sensor value = on``` to change the input to the button on the Pibrella.

