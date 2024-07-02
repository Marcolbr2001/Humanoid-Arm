# Humanoid-Arm

<it> _The humanoid arm is one of the most relevant projects. It is realised with a 3D printer and the help of 8 servomotors controlled by one Arduino Mega board and other electronics._ </it>

<div align="center">

[https://github.com/Marcolbr2001/6502_Computer/assets/66978947/5fb89dd2-7d88-45e0-95bd-d183eab47c54](https://github.com/Marcolbr2001/Humanoid-Arm/assets/66978947/865c951f-4a17-40af-a558-76ea20866bf0
)

</div>

## Inside the Arm

<pre>
  
- Used Materials
- 3D Printed Case
- x8 servomotors
- x1 Arduin MEGA
- x1 TouchPad
- x2 3.3V Li Batteries
  
</pre>



<p align="center">
  <img src="https://github.com/Marcolbr2001/Humanoid-Arm/assets/66978947/d4844856-6183-4494-bc8f-be5d326f4987" width="600" title="hover text">
  <!--<img src="https://github.com/Marcolbr2001/6502_Computer/assets/66978947/97c4f9f9-d9a5-4a7c-9f70-d55d0c68c5f6" width="350" alt="accessibility text">-->
</p>


For the movement of the hand and fingers are 6 small servomotors were used (1 for the wrist, 5 for the fingers) with torque 1,6kg/cm. The inner rib in Nayoln, which can be noted in the picture on the right, allows the 5 servomotors to pull or push individual fingers, thus making an opening or closing.

The movement of the elbow and shoulder is made possible by 2 other servomotors, this time with a torque of 20 kg/cm.

## Code
Motion commands have been given, such as you can see at the end of the video, through two simple Arduino boards One that only later will be replaced by a single card. The code is quite simple, it is in fact only a precise sequence of actions: shoulder rotation, elbow rotation, hand opening, hand closure, wrist rotation.

<p align="center">
  <img src="https://github.com/Marcolbr2001/6502_Computer/assets/66978947/97c4f9f9-d9a5-4a7c-9f70-d55d0c68c5f6" width="600" title="hover text">
  <!--<img src="https://github.com/Marcolbr2001/6502_Computer/assets/66978947/97c4f9f9-d9a5-4a7c-9f70-d55d0c68c5f6" width="350" alt="accessibility text">-->
</p>

