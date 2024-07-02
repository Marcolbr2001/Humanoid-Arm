# Humanoid-Arm

## Inside the Arm

<pos>
  
- Used Materials
- 3D Printed Case
- x8 servomotors
- x1 Arduin MEGA
- x1 TouchPad
- x2 3.3V Li Batteries
  
</pos>

For the movement of the hand and fingers are 6 small servomotors were used (1 for the wrist, 5 for the fingers) with torque 1,6kg/cm. The inner rib in Nayoln, which can be noted in the picture on the right, allows the 5 servomotors to pull or push individual fingers, thus making an opening or closing.

The movement of the elbow and shoulder is made possible by 2 other servomotors, this time with a torque of 20 kg/cm.

## Code
Motion commands have been given, such as you can see at the end of the video, through two simple Arduino boards One that only later will be replaced by a single card. The code is quite simple, it is in fact only a precise sequence of actions: shoulder rotation, elbow rotation, hand opening, hand closure, wrist rotation.
