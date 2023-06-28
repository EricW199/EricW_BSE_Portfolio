# Emotional Responsive Robot
My Project is the Emotionally Responsive Robot. It's a Robot that reacts to sudden movements and can be controlled via Bluetooth to control its emotions. In my project, there are several components that are used to imitate its reactions such as servos, supersonic sensors, and Bluetooth module. Its servos can be used for movement, supersonic sensors to detect sudden movements, and a bluetooth module to connect your phone to control its emotions.

| Eric W. | Vacaville Christian School | Mechanical Engineering | Incoming Junior |
|::|:--:|:--:|


<!--- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)

  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What do you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="(https://www.youtube.com/watch?v=0YXdgLMgcYM&ab_channel=BlueStampEng)" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->
# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/VuyLpELa1uM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

During my first milestone, I had to solder components onto my wave shield and wire LED matrixes, LCD displays, and ultrasonic sensors onto my wave shield. My ultrasonic sensors can be used to track distance using high frequencies and receiving those frequencies, tracking how long it took to receive them to track distance. My LCD shows the distance captured from the ultrasonic sensor. My LED matrixes are used to display as eyes of the robot. You Also needed many different Arduino libraries such as LiquidCrystalI2C. My biggest challenge was I had many ineffective wires connected to my components and had to rewire most of them, and My Arduino Uno wasn't detecting my wave shield, so had to resolder it to connect. For my next milestone, I plan to create an app to control the head movements and emotions of the robot and attach servos to control its eyebrow movement, head movements, and eye expressions.

# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/0YXdgLMgcYM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My starter project is the digital clock. It's a digital clock that can display time, day, week, month, year, and temperature. This digital clock consists of many components such as thermistors and buttons. Thermistors are used to detect the temperature, and the buttons are used to switch between the modes to display the day or temperature. My biggest challenge while doing this starter project was searching for each component since I had no idea what they looked like. My next project is going to be an emotionally responsive robot that reacts to motion and can be controlled via Bluetooth. 





<!--- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resources because LCDs to create professional schematic diagrams, though BSE recommends Tinkercad because it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  /Putt your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  /Putt your main code here, to run repeatedly:

}
```
-->
# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Uno | programmable microcontroller board | $28.50 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Adafruit wave shield | adding audio | $26.82 | <a href="https://www.amazon.com/Adafruit-Wave-Shield-Arduino-Kit/dp/B00IQXZN9Q/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 2x 8x8 LED Matrixes | display as eyes | $7.99 | <a href="https://www.amazon.com/DIYables-Display-Arduino-ESP8266-Raspberry/dp/B0BXKM66XX/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 16x2 LCD Character Display w/ I2C backpack | display messages | $8.99 | <a href="https://www.amazon.com/SunFounder-Serial-Module-Display-Arduino/dp/B071Y6JX3H/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 2x MG995 Servo Motor | pan and tilt head | $18.99 | <a href="https://www.amazon.com/180%C2%B0High-Torque-Helicopter-Airplane-Futaba/dp/B07PFD6H31/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Pan Tilt Servo Brackets | making multi axis joints | $6.43 | <a href="https://www.amazon.com/Bracket-Sensor-Multifunction-Bearing-Screws/dp/B0B3Y7ZXZD/"> Link </a> |
|:--:|:--:|:--:|:--:|
| HC-SR04 Ultrasonic Sensor | Track distance | $1.80 | <a href="https://www.amazon.com/Organizer-Ultrasonic-Distance-MEGA2560-ElecRight/dp/B07RGB4W8V/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 2 Watt 8 Ohm Small Speaker | Output for audio | $3.94 | <a href="https://www.amazon.com/Gikfun-Speaker-Diameter-Arduino-AE1054/dp/B01EJI8UWI/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 4 AA Battery Holder with Vdd and Gnd Wires | power source | $3.24 | <a href="https://www.amazon.com/LAMPVPATH-Battery-Holder-Leads-Wires/dp/B07T7MTRZX/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 2x SG90 9G Micro Servos | move eyebrows | $7.29 | <a href="https://www.amazon.com/Sipytoph-Helicopter-Airplane-Walking-Control/dp/B09185SC1W/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 40p 200mm Male-to-Female Dupont Cables | interconnect components | $3.25 | <a href="https://www.amazon.com/GenBasic-Solderless-Dupont-Compatible-Breadboard-Prototyping/dp/B01L5UKAPI/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 40p 200mm Female-to_Male Jumper Cables | connect electric circuits to circuit boards | $12.49 | <a href="https://www.amazon.com/uxcell-Female-Jumper-2-54mm-Breadboard/dp/B07GN85RC2/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 8 GB microSDHC Class 4 Flash Memory Card SDC4/8GBET | insert into wave shield | $9.99   | <a href="https://www.amazon.com/Kingston-Class-MicroSDHC-Memory-Adapter/dp/9983039281/"> Link </a> |
|:--:|:--:|:--:|:--:|
| HC-05 Wireless Bluetooth RF Transceiver | connect android device | $10.39 | <a href="https://www.amazon.com/HiLetgo-Wireless-Bluetooth-Transceiver-Arduino/dp/B071YJG8DR/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Breadboard with 2 Power Rails and 50p Jumper Cables | connecting components | $11.99 | <a href="https://www.amazon.com/HUAREW-Breadboard-Jumper-Include-Points/dp/B09VKYLYN7/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 4x 5/8 steel screw | securing components | $0.44 | <a href="https://www.amazon.com/Sentry-Supply-651-0358-8-Inch-Chrome/dp/B00DUQ9NK4/"> Link </a> |
|:--:|:--:|:--:|:--:|  
| 8x 4-40x3/4 steel screw | securing components | $0.56 | <a href="https://www.amazon.com/Phillips-Machine-Screws-Stainless-Thread/dp/B01HQ6UP32/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 12x 4-40x1/2 steel screw | securing components | $0.27 | <a href="https://www.amazon.com/2500pcs-4-40x1-Socket-Button-Stainless/dp/B06XF1W9TQ/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 20x 4-40 steel nut | securing components | $0.40 | <a href="https://www.amazon.com/Steel-Hex-4-40-Threads-Pack/dp/B000N2YSU8/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 4x 6-32x1/2 oval | securing components | $0.29 | <a href="https://www.amazon.com/Prime-Line-Products-MP9191-Construction-Slotted/dp/B01MA6EMXH/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 4x 6-32 nut | What the item is used for | $0.64 | <a href="https://www.amazon.com/Instockbolts-Nylon-Insert-Stainless-Steel/dp/B09V4T41WL/"> Link </a> |
|:--:|:--:|:--:|:--:|
<!---
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|


# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
