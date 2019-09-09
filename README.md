# IDD-Fa18-Lab1: Blink!

**A lab report by Sandra Ebirim*

> Include your responses to the bold questions on your own fork of the lab activities. Include snippets of code that explain what you did. Deliverables are due next Tuesday. Post your lab reports as `README.md` pages on your GitHub, and post a link to that on your main class hub page.

We've copied the questions from the lab here. Answer them below!

## Part A. Set Up a Breadboard

[[https://github.com/sandraebirim/IDD-Fa18-Lab1/blob/master/breadboard.HEIC]]


## Part B. Manually Blink a LED

**a. What color stripes are on a 100 Ohm resistor?**
 
**b. What do you have to do to light your LED?**

I needed to push the button in order to complete the circuit. 

## Part C. Blink a LED using Arduino

### 1. Blink the on-board LED

**a. What line(s) of code do you need to change to make the LED blink (like, at all)?**

Nothing was changed to from the original code in order to make the LED blink. Simply running the original code caused the LED light to blink. 

**b. What line(s) of code do you need to change to change the rate of blinking?**

The amount of time in each of the delays. The longer the delay, the light was perceived as blinking at a slower rate while decreasing the amount of time caused the light to blink more quickly. 

**c. What circuit element would you want to add to protect the board and external LED?**

Adding a resistory would protect the board and an external LED BECAUSE 
 
**d. At what delay can you no longer *perceive* the LED blinking? How can you prove to yourself that it is, in fact, still blinking?**

Decreasing the delays to 15 milliseconds essentially changed the LED into a continuous stream. 

**e. Modify the code to make your LED blink your way. Save your new blink code to your lab 1 repository, with a link on the README.md.**


### 2. Blink your LED

**Make a video of your LED blinking, and add it to your lab submission.**

[link to your video here; feel free to upload to youtube and just paste in a link here]


## Part D. Manually fade an LED

**a. Are you able to get the LED to glow the whole turning range of the potentiometer? Why or why not?**


## Part E. Fade an LED using Arduino

**a. What do you have to modify to make the code control the circuit you've built on your breadboard?**

In order to change the led that is being manipulated, the int led = 9 line must be altered to int led = 11. 
**b. What is analogWrite()? How is that different than digitalWrite()?**

analogWrite() can control the percentage of time that the LED light is on while digitalWrite() can only turn the light to the HIGH voltage (which turns the light on and is 5V in this case) or the LOW voltage (which is ground or 0 in this case). 

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
