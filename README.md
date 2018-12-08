Code of our Major project - "Gesture controlled mobile robotic arm"  for disabled people to interact independently 
with their environment and other remote applications.
 
Use Python 2.7, press escape to exit live video feed, comment arduino related code if you don't have an arduino 
connected and use the right COM port in the code if you do have an Arduino connected. Making a new environment 
in Anaconda with Python 2.7 is recommended.

The robotic arm's gripper servo is controlled with inputs from the keyboard. We used a handheld wireless keyboard.
We have set the inputs as '=' (for +, to increase angle, open the claw) and '-' (for -, to decrease angle, close the claw)

Methodology: -
We have used the position and size of a Yellow glove in webcam's video feed to control the three servos and inputs from a wireless keyboard to control the fourth servo. (Gripper's servo) Servo angles are sent wirelessly from the laptop to an Arduino using point to point communication using Xbee radio modules.
Xbee tutorial: -https://www.youtube.com/watch?v=cf3RLBg4t5s&list=PLSaHroqSzd_UKJYMf1k8Louckzl5ZAhV2&index=2&t=0s 

For visual feedback, we have live streamed video using Wi-Fi in our web browser using the MPJG streamer and the Raspberry Pi Camera. 
https://www.gadgetdaily.xyz/control-your-raspberry-pi-robot-from-a-web-connected-device/ 

Future Scope: -
1. Make a web browser controlled mobile base of the robotic arm.
2. Make it voice controlled for easy use by handicapped people.
3. Make the robotic arm completely mobile using a reliable power source for the Raspberry Pi 3B+, RPi camera, servos and the Arduino.

Links: -
Link to Poster: https://docs.google.com/presentation/d/1ageNDzJ2luRFndFu3ZjqOV9EqiWc-VZq-yEJiXpjJYI/edit?usp=sharing 

Link to PPT:  https://docs.google.com/presentation/d/1M2q5kQhTZYJuNN5PDeFdrQMJS3ilbD9N_m0oiw22n7o/edit?usp=sharing 

We have used the open source MeArm for our project.
Link for dxf file for laser cutting (Use Corel draw to open it)- https://www.thingiverse.com/thing:993759 
MeArm Assembly instructions: -
https://www.instructables.com/id/MeArm-Robot-Arm-Your-Robot-V10/ 
Credits: -
We are indebted to Joe MacInnes for custom functions and formulas to calculate servo angles. 
Thanks to Tushar Singh Teotia for making the video!

