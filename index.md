## Electric Scateboard

On the first day of my build, I made some sketch designs and research the types of motors, batteries, and boards I would need to use. I also went around my house to see if I could find anything to cut my cost down. Eventually, I found my old Ripstick and wondered if I could use that instead of buying an entirely new skateboard. I ordered all the parts I thought I needed and waited. However, later on in the build, I went over to my friend’s house to play and saw he had an old kids skateboard he did not use so I decided I wanted to try and build on it. This caused me to redesign my entire build and had to reorders some different parts.

### Parts list
On the day the parts came, the things that came were:
ESC
Arduino Pro Micro
AC Brushless motor
Long Board Trucks
Long Board Wheels
Two 7.4, 2S, Lipo Batteries

I tried assembling all the parts together to see whether or not it would fit and had to file a few parts down for clearance. Next, I had to work on making the speed controlling and transceiver. I had a soldering kit and proto boards and just needed a working prototype on a breadboard to see if it would work. I saw a  guide online showing that you could have wireless communications using an nrf24l01 to send and receive things. When I went to test all the parts together many parts would fail either due to over heading or wrong rating and I would have to replace them.

The final product is able to drive forward and I am trying to implement a feature where the Arduino can check the amount of voltage the batteries had and display it with an OLED screen. Currently, below is what my project looks like. The code is on my [Github](https://github.com/agmui/Arduino_Projects.git). Some guides I found realy useful for using the nrf24L01 was from [howtomechatronics](https://howtomechatronics.com/tutorials/arduino/arduino-wireless-communication-nrf24l01-tutorial/).
