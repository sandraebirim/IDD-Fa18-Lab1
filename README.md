# IDD-Fa18-Lab1: Blink!

#### A lab report by Sandra Ebirim


## Part A. Set Up a Breadboard

Image of breadboard: ![Image of breadboard](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/breadboard.jpeg)


## Part B. Manually Blink a LED

**a. What color stripes are on a 100 Ohm resistor?**
 
 A 100 Ohm resistor has the following stripes: Brown, Black, Brown, Gold. 
 
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
To prove to myself that it was still blinking, I could write a function that prints each time the light turns on or off. 

**e. Modify the code to make your LED blink your way. Save your new blink code to your lab 1 repository, with a link on the README.md.**

[Blinking Code](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/blink.ino)

### 2. Blink your LED

**Make a video of your LED blinking, and add it to your lab submission.**

[External LED Blinking Video](https://youtu.be/97DIe4FubD4)


## Part D. Manually fade an LED

**a. Are you able to get the LED to glow the whole turning range of the potentiometer? Why or why not?**

Yes, the potentiometer functions as a variable resistor. As resistance decreases, the amount that the light glows increases, unnoticeably at first but more noticably after passing the halfway point on the potentiometer. The light doesn't go entirely out because the resistance on the potentiometer never goes high enough to entirely prevent current from runnibng through the LED. 

[Potentiometer](https://youtu.be/mG-0--jWLEM)

## Part E. Fade an LED using Arduino

[Fade Video](https://youtu.be/EdQN_qhOrHM)

**a. What do you have to modify to make the code control the circuit you've built on your breadboard?**

In order to change the led that is being manipulated, the following line had to be altered from: 
![Original](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/int9.png)

to ![Changed](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/int11.png) to reflect where the LED light is attached to the breadboard. 

**b. What is analogWrite()? How is that different than digitalWrite()?**

analogWrite() can control the percentage of time that the LED light is on while digitalWrite() can only turn the light to the HIGH voltage or the LOW voltage. 

## Part F. FRANKENLIGHT!!!

### 1. Take apart your electronic device, and draw a schematic of what is inside. 

Schematic of inside of calculator ![Schematic of inside of calculator](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/calculator%20system%20design.jpeg) 

**a. Is there computation in your device? Where is it? What do you think is happening inside the "computer?"**

From this image ![this image](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/calculator.jpeg), I would assume the computation for this calculator takes place in the black circular object. In this "computer", I would assume that it is taking in the numbers that are being pushed, displaying the numbers, and then doing the appropriate calculations. 

**b. Are there sensors on your device? How do they work? How is the sensed information conveyed to other portions of the device?**

There are no sensors on the calculator. 

**c. How is the device powered? Is there any transformation or regulation of the power? How is that done? What voltages are used throughout the system?**

The calculator is powered by a 3V battery where the power is transformed by the circuit to be utilized to power the LED and to connect the buttons to the "computer" and LED. 

**d. Is information stored in your device? Where? How?**

The numbers and processes required for calculations must be stored, most likely in the black "computer" component. 

### 2. Using your schematic, figure out where a good point would be to hijack your device and implant an LED.

**Describe what you did here.**

On the board, there is an exposed battery and a cirlce notated with GND, indicating ground. There are also 2 LED lights on the back on the board that have no clear use but also have positive ends notated as well. I chose to hijack one of these two lights, connect to a breadboard, and use a button on the breadboard to turn on and off the light. 

### 3. Build your light!

**Make a video showing off your Frankenlight.**

[Frankenlight](https://youtu.be/f7pST5Y3Xb0)
Frankenlight Schematic: ![Frankenlight Schematic](https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/frankenlight.jpeg)
**Include any schematics or photos in your lab write-up.**
