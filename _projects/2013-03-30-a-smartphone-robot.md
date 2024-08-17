---
layout: page
title: A Smartphone Robot
date: 2013-03-30T16:31:06+00:00
permalink: /projects/smartphone-robot/
img: /assets/img/BotFinal.png
category: electronics
tags: [Android, Arduino, MATLAB, Robot,Smartphone, Smartphone Robot]
comments: true
---

Yes ! You heard it right ! It is a robot with your smartphone mounted on it.

Why should you do it ?

1. Fun: What is cooler than using that old android phone which was not being used to make your own robot with loads of functionalities !

2. Learning: Learn basic robotics tasks like driving a motor and connection mechanisms, in this case, bluetooth and a little tinge of MATLAB for creating the GUI.

It started off as a thought of making something interesting enough so that I would make sincere efforts to get it work. I identified that a robot which can be wirelessly controlled and communicate data from a set of sensors would be a good idea to work on. Over some days, as the idea matured, I decided to use a smartphone instead of using the individual sensors. Not only would using the individual sensors make the system difficult to bring up but it would cost a lot. A smartphone has a whole variety of sensors and actuators, namely mic, camera, display, speakers, accelerometer that it was perfect for the system I was trying to make. This way, we could make it compatible to anybody's phone and make it an easy DIY project.

Since I already had my old phone lying around, it also gave us cost efficiency. A second hand phone is worth pennies anyway, why not build an awesome robot for yourself.

Here is the block diagram I thought of.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/smartphone-bot-comm.png' | relative_url }}" alt="" title="example image"/>
	</div>
</div>
<div class="caption">
Block diagram of the system
</div>

Since I already had experience with Arduino, the last two pieces were a piece of cake. Just wire things up and write the code. The challenging part was the Android Application, PC Application and the Bluetooth connectivity for the arduino to interact with the phone. I wanted the phone to be easily detachable, so I wanted to use the bluetooth only and not any other interface. A friend Ashish volunteered to join the project for the android app development. The Android application was required to relay the signals it receives over Wifi to the Arduino, so that the bot can be controlled anywhere in the house as long as it is connected to the Wifi. Here's a link to the <a href="https://play.google.com/store/apps/details?id=com.bluetooth2" target="_blank">app</a>.

**The Android Smartphone ** streams the video from its camera to the PC, with the help of an application called <a href="https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en" target="_blank">IP Webcam</a> (yes it is pretty awesome).

**The PC Application **developed in MATLAB using the utility GUIDE, is used to receive the video, to send the control signals back to the phone, which in-turn communicates it to the Bluetooth present on an Arduino Shield.

<a href="http://arduino.cc/" target="_blank">Arduino</a> is probably the biggest name in open source hardware. Arduino Shields are nothing but circuits stacked onto Arduino with the help of pinheads. It provides an easy to use mechanism for rapidly prototyping your circuits. Bluetooth was ordered from <a href="http://www.rhydolabz.com/index.php?main_page=product_info&products_id=1159" target="_blank">here</a>.

DC **Motors** were used for driving the robot, obtained from <a href="http://www.pololu.com/catalog/product/1093" target="_blank">here</a>. Yes, they are costly but they make the robot look great ! You can alternatively use cheaper motors you obtain from your local market.

Here is the schematic diagram of the connections you will need to make.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/smartphonebot-schematic.jpg'| relative_url }}" alt="" title="Schematic Diagram"/>
    </div>
</div>
<div class="caption">
	Schematic Diagram of the Smartphone Bot.
</div>


You can access the codes for the GUI and the code used in Arduino from <a href="https://docs.google.com/file/d/0B_5eRz5cayvXMWhESk5wbVBqX0E/edit?usp=sharing" target="_blank">here</a>.

The initial design was something like this:

<div class="row justify-content-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/InitialDesign.png'| relative_url }}" alt="" title="Schematic Diagram"/>
    </div>
</div>
<div class="caption">
	The initial design was more compact but not stable. 
</div>

This human like bot had a great turning radius, but wasn't very stable. The phone stand was drilled into the laser cut bottom and the arduino was mounted on the same. We decided to go with a much more aesthetically pleasing and stable bot for the final version. The design was made and laser cut. The final bot looked like this:

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/BotFinal.png'| relative_url }}" alt="" title="Final Prototype"/>
    </div>

    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/CentreOfMass.png'| relative_url }}" alt="" title="Center of Mass"/>
    </div>
</div>
<div class="caption">
	The center of mass is designed to be in the center.	
</div>


Beauty! Isn&#8217;t it? 🙂

The design was much more stable because of the weights being distributed properly. An analysis of the weight distribution is as illustrated below:

The battery was placed below the Arduino, further stabilizing the robot. Overall, it was a fun experience. The thing that amazed me the most was that we worked on so many different platforms.

  * Windows &#8211; For the GUI Development
  * Android &#8211; For the Mobile App
  * Arduino &#8211; For the Embedded code/Hardware Interaction
  * Hardware Design &#8211; For the chassis

It was a very rewarding experience for all of us, and ofcourse, the sight of our hard work was very satisfying.
