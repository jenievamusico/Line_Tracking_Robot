Readme.txt

1. what can your robot do?
The robot is capable of trapping the crate with its arm, when it is in its specified proximity, by using the ultrasound sensor.
After taking the crate, the robot tracks the line on its right side (default) with the light sensor. Then, the crate is delivered to
the red target zone by raising the arm.

Using a different set of code, the robot has the ability of delivering the crate to the intersection of the split road and once 
delivered the robot flashes "delivery successful" 3 times. The robot can also detect which side of the line it is placed on, before 
tracking the line on a randomly placed side.


2. what can't your robot do?
The robot is not capable of detecting how long the length of the split road is, go to end of it and then back to the main road. 

In the smartbot file, it can’t find the line when it’s on the right side because we didn’t have time to change the colour sensor value to 
less than 20 after realizing that it was reading a much lower value than in the other two files. 

Also, in the smartbot code both sides don’t reach the delivery spot because we ran out of time to change the encoder value to the proper 
distance.


3. what have you observed as differences between the virtual and physical twin?
with the physical twin, one is able to control what side of the track the robot starts, where as in the virtual world it will always 
start on the right (default) side meaning the code for the physical robot might be a little different than the virtual robot.

4. other comments you wish to forward to developers working on this project in the future, or users of your product.
Be mindful of the colour surface you are using, aswell as what value the colour of the line is being sensed. Also, sometimes slower 
is better when it comes to the speed of the motors as the physical robot may react differently on the track than on the virtual world. 