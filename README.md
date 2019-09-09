# IDD-Fa18-Lab1: Blink!

**A lab report by Sandra Ebirim*

> Include your responses to the bold questions on your own fork of the lab activities. Include snippets of code that explain what you did. Deliverables are due next Tuesday. Post your lab reports as `README.md` pages on your GitHub, and post a link to that on your main class hub page.

We've copied the questions from the lab here. Answer them below!

## Part A. Set Up a Breadboard

![Image of breadboard](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/breadboard.jpeg)


## Part B. Manually Blink a LED

**a. What color stripes are on a 100 Ohm resistor?**
 
 A 100 Ohm resistor has the following stripes: Brown, Black, Brown, Gold. 
 The resistor we are using is 220 Ohms and has the colors Brown, Black, Black, Red, Red. 
 
**b. What do you have to do to light your LED?**

I needed to push the button in order to complete the circuit as well as connecting the breadboard to an energy source. 

## Part C. Blink a LED using Arduino

### 1. Blink the on-board LED

**a. What line(s) of code do you need to change to make the LED blink (like, at all)?**

Nothing was changed from the original code in order to make the LED blink. Simply running the original code caused the LED light to blink. 

**b. What line(s) of code do you need to change to change the rate of blinking?**

The amount of time in each of the delays. The longer the delay, the light was perceived as blinking at a slower rate while decreasing the amount of time caused the light to blink more quickly. 

**c. What circuit element would you want to add to protect the board and external LED?**

Adding a resistor would protect the board and external LED because it limits the amount of current running through the ciruit. 
 
**d. At what delay can you no longer *perceive* the LED blinking? How can you prove to yourself that it is, in fact, still blinking?**

Decreasing the delays to 15 milliseconds essentially changed the LED into a continuous stream. 
![Delay](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/delay.png)

**e. Modify the code to make your LED blink your way. Save your new blink code to your lab 1 repository, with a link on the README.md.**

[Blinking Code](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/blink.ino)

### 2. Blink your LED

**Make a video of your LED blinking, and add it to your lab submission.**

[External LED Blinking Video](https://youtu.be/97DIe4FubD4)


## Part D. Manually fade an LED

**a. Are you able to get the LED to glow the whole turning range of the potentiometer? Why or why not?**

Yes, the potentiometer functions as a variable resistor. As resistance decreases, the amount that the light glows increases, unnoticeably at first but more noticably after passing the halfway point on the potentiometer. 


## Part E. Fade an LED using Arduino

**a. What do you have to modify to make the code control the circuit you've built on your breadboard?**

In order to change the led that is being manipulated, the following line had to be altered from: 
![Original](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/int9.png)

to ![Changed](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/int11.png) to reflect where the LED light is attached to the breadboard. 

**b. What is analogWrite()? How is that different than digitalWrite()?**

analogWrite() can control the percentage of time that the LED light is on while digitalWrite() can only turn the light to the HIGH voltage or the LOW voltage. 

## Part F. FRANKENLIGHT!!!

### 1. Take apart your electronic device, and draw a schematic of what is inside. 

**a. Is there computation in your device? Where is it? What do you think is happening inside the "computer?"**

**b. Are there sensors on your device? How do they work? How is the sensed information conveyed to other portions of the device?**

**c. How is the device powered? Is there any transformation or regulation of the power? How is that done? What voltages are used throughout the system?**

**d. Is information stored in your device? Where? How?**

### 2. Using your schematic, figure out where a good point would be to hijack your device and implant an LED.

**Describe what you did here.**

### 3. Build your light!

**Make a video showing off your Frankenlight.**

**Include any schematics or photos in your lab write-up.**
