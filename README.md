# LED-CUBE-8x8x8-
a three dimensional led display ,consisting of (8x8x8) ,512 led lights.
<p align="left">
  <img  src=snap_shots/img1.jpeg><br>
</p>

 - A led cube in Action <br>

 ## Idea
 <p align="left">
 
  So,this whole idea strike to my mind ,when I was participating in very first TechFest event during first year of my college,there I saw the similar model build by someone,which was very interesting and actractive too, to be very honest ,at that moment I was felling like a noob,and there only I decided that one day ,I will make a similar model,after that I started searching about that everywhere like insane, then I got to know about ,there is something called **ARDUINO** ,which is like backbone of this whole model. After that I researched more about Arduino ,watched twenty+ videos on youtube ,read different Aticle and blogs about LED CUBE in different website, one such website is *:https://www.instructables.com/Led-Cube-8x8x8/* ,this clear most of my queries about the procedure and how to initiate this project,also, this github repo helped me alot *:https://github.com/itsharryle/LED_CUBE*. 
  </p>
<p align="left">
  before building the big 8x8x8 LedCube ,it was suggested to start with a small cube,so I did the same and started with a 3x3x3 LedCube,which helped me a lot,like how to build the basic structure of the cube,here is the snap shot, during I was build the small cube.
  </p><br>
 
 <p align="left">
  <img  src=snap_shots/img2.jpeg width="1280" height="640"><br>
  
  - Structure of a small 3x3x3 led cube.
</p>
<p align="left">
 after building the small cube ,I pluged the arduino to my laptop and it started working fine👍
  </p><br>
   <p align="left">
  <img  src=snap_shots/img3.jpeg><br>

   - working of the small 3x3x3 LedCube
</p>
<p align="left">

**CUBE STRUCTURE:** <br>
 then I arranged all the required components for making the 8x8x8 LedCube, these are as follows:<br>
1: LEDs x 512 <br>
2: 21 AWG  copper wire<br>
3: Wires<br>
4: PN2222 transistors x 16<br>
5: 220-ohm resistors x 64<br>
6: 74HC595 shift registers x 9<br>
7: Arduino Uno<br>
8: Pushbutton<br>
9: 5V 2Amp power supply<br>
it is more difficult for making an RGB LedCube, so I decided to use a color combination of red, yellow, green, and blue LEDs, and made the whole cube by maintaining the symmetrical pattern, the result was pretty awesome, here I would suggest you, not to use any wire which is less than 20AWG, because, you will face difficulty when you start making the cube. <br>
in each of eight layers consisting of (8x8) LEDs, I connected cathode(negative) of all LEDs together, and connected anode(positive) of all LEDs(8, one from each layer) which were in the same column, together.
So in the end I had (8x8) 64 anodes and 8(one from each layer) common cathodes. Make sure that you have checked all the LEDs before making the structure, also check for proper connection of wires.<br>
these tutorials are very helpful for building the structure:<br>

- *https://youtu.be/mN5JWQUfrxY*<br>
- *https://youtu.be/JqBGBm2iza8*<br>

  </p><br>
  
   <p align="left">
  <img  src=snap_shots/img4.jpg width="1280" height="640"><br>

   - Structure of 8x8x8 LedCube
</p>
<p align="left">

**CIRCUIT:**<br>
I searched a lot for a proper circuit diagram, and finally, the one provided in this repo worked for me with some troubleshooting, My father who used to do electronics stuff, helped me for making a fully functional circuit from scratch. Here, one problem that I had faced was related to the power supply, in the starting, I was using a *5V 700mAps DC*, but that wasn't sufficient to lighten up the whole cube with its full intensity, then I switched to a *5V 2Amps* of powerSupply and served my purpose. <br>
</p>

 </p><br>
   <p align="left">
  <img  src=snap_shots/img5.jpg width="1280" height="640"><br>

   - a circuit made from scratch.
</p>

<p align="left">

**CODE:**<br>
this was the most interesting part of the whole project, I searched a lot for a properly documented code but haven't got any code which worked for me, the way I wanted, though they were very helpful and most of them were similar, so "Kudos" to the programmer who wrote those code. I used one such code and did some changes, and it worked.<br>
I had added the *continuous voxel drop* pattern, and still working to add more patterns like SineWaves, FireWorks, etc, if you have any idea how to implement those patterns, please contribute to this repo:<br>
https://github.com/Anubhaw19/LED-CUBE-8x8x8


</p>
  

 
 
 ## Final Result (checkout this video on youtube)  👇
[![Watch the video](https://img.youtube.com/vi/BIYr0ZdlVQI/maxresdefault.jpg)](https://youtu.be/BIYr0ZdlVQI)
