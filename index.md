# Emotional Responsive Robot
My Project is the Emotionally Responsive Robot. It's a Robot that reacts to sudden movements and can be controlled via Bluetooth to control its emotions. In my project, several components are used to imitate its reactions such as servos, ultrasonic sensors, and Bluetooth module. Its servos can be used for movement, ultrasonic sensors to detect sudden movements, and a Bluetooth module to connect your phone to control its emotions.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Eric W. | Vacaville Christian School | Mechanical Engineering | Incoming Junior |



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
-->

# Final Milestone
For my final milestone, I attached 2 servos to control the robot's head movement, so the head moves left, right, up, and down. This milestone was mainly assembly of the robot so screwing all my 3d printed parts and components into the main body of the robot. Its head can be controlled by the app that I made in MIT App Inventor and if the ultrasonic sensor detects a nearby object it gets surprised which freaks out and its head movement becomes faster and more random. My biggest challenge with this whole project was finding errors in my code and how to fix them, like why was my head not moving. Sometimes I needed to test if it was a software or hardware problem. My biggest challenge was my eyes as I was stumped on them for about 2 days and I was too stubborn to ask for help. During my time at BSE, I learned that things need to be achieved yourself, you can't always expect help from peers. 
# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/sZYrgeUFZfM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!--- For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->
In this milestone, I coded my LED matrices and eyebrow servos to react to different emotions transmitted by my Bluetooth module. To transmit messages to my Arduino I installed this app that I created on MIT App Inventor that sends various bytes that communicates with the Arduino that I want this emotion to display. The robot can display happiness, sadness, anger, surprise, love, and neutrality. However, surprise isn't an emotion controlled by the app but by the ultrasonic sensor, when it senses that an obstacle is nearby the robot starts moving rapidly as if it was in a panic to show this surprise emotion. My biggest challenge with this milestone is trying to get my LED matrices to display different eyes like the left eye is different than the right eye. The reason I had so many troubles with my eyes was that the code was meant for Adafruit 8x16 Led Matrix but instead, I had 2 8x8 Led Matrices causing me to adjust all the code that had anything to do with the eyes. Also, my Android device wouldn't connect to the Bluetooth module, to fix this you need to change the app permissions to access nearby devices so that your app gains access to the Bluetooth module.  There were many problems with my code like some brackets in the code weren't matched with the correct line of code. My plans for the next milestone are mainly the assembly of the robot, connecting my pan and tilt servos to control the robot's head movement, and coding my app to also control head movement. 

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/VuyLpELa1uM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

During my first milestone, I had to solder components onto my wave shield and wire LED matrixes, LCDs, and ultrasonic sensors onto my wave shield. My ultrasonic sensors can be used to track distance using high frequencies and receiving those frequencies, tracking how long it took to receive them to track distance. My LCD shows the distance captured from the ultrasonic sensor. My LED matrixes are used to display as eyes of the robot. You Also needed many different Arduino libraries such as LiquidCrystalI2C. My biggest challenge was I had many ineffective wires connected to my components and had to rewire most of them, and My Arduino Uno wasn't detecting my wave shield, so had to resolder it to connect. For my next milestone, I plan to create an app to control the head movements and emotions of the robot and attach servos to control its eyebrow movement, head movements, and eye expressions.

# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/0YXdgLMgcYM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My starter project is the digital clock. It's a digital clock that can display time, day, week, month, year, and temperature. This digital clock consists of many components such as thermistors and buttons. Thermistors are used to detect the temperature, and the buttons are used to switch between the modes to display the day or temperature. My biggest challenge while doing this starter project was searching for each component since I had no idea what they looked like. My next project is going to be an emotionally responsive robot that reacts to motion and can be controlled via Bluetooth. 





<!--- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resources because LCDs to create professional schematic diagrams, though BSE recommends Tinkercad because it can be done easily and for free in the browser. 
-->
# Code

<details markdown="1"> 

```

c++
/*************************************************************
//  Brobot: Main File
//  This file contains the setup and execution loop for the Arduino
//  while Brobot is in operation.
//  Project Inspiration: Chris Frazier
//  Modified by Eric W.
//  Date: 7/13/2023
**************************************************************/

#include "Wire.h"
#include "SoftwareServo.h"
#include "Adafruit_LEDBackpack.h"
#include "Adafruit_GFX.h"
#include <Brobot.h>
#include <LiquidCrystal_I2C.h>
#include "WaveHC.h"

#define panPin 14        // This is the pan servo pin
#define tiltPin 15       // This is the tilt servo pin
#define leftBrowPin 16   // This is the left eyebrow servo pin
#define rightBrowPin 17  // This is the right eyebrow servo pin
#define echoPin 12        // This is the echo pin
#define triggerPin 7     // This is the trigger pin

// Create an instance of Brobot
Brobot myBrobot(panPin, tiltPin, leftBrowPin, rightBrowPin, echoPin, triggerPin);

void setup() {
  Serial.begin(9600);  // Set baud rate for serial protocol

  putstring("Free RAM: ");             // This can help with debugging, running out of RAM is bad
  Serial.println(myBrobot.freeRam());  // if this is under 150 bytes it may spell trouble!

  // Set the output pins for the DAC control. This pins are defined in the library
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);

  //  if (!card.init(true)) { //play with 4 MHz spi if 8MHz isn't working for you
  if (!myBrobot.card.init()) {           //play with 8 MHz spi (default faster!)
    putstring_nl("Card init. failed!");  // Something went wrong, lets print out why
    myBrobot.sdErrorCheck();
    while (1)
      ;  // then 'halt' - do nothing!
  }

  // enable optimize read - some cards may timeout. Disable if you're having problems
  myBrobot.card.partialBlockRead(true);

  // Now we will look for a FAT partition!
  uint8_t part;
  // for (part = 0; part < 5; part++) {     // we have up to 5 slots to look in
  //   if (myBrobot.vol.init(myBrobot.card, part))
  //     break;                             // we found one, lets bail
  // }
  // if (part == 5) {                       // if we ended up not finding one  :(
  //   putstring_nl("No valid FAT partition!");
  //   myBrobot.sdErrorCheck();      // Something went wrong, lets print out why
  //   while(1);                            // then 'halt' - do nothing!
  // }

  // // Lets tell the user about what we found
  // putstring("Using partition ");
  // Serial.print(part, DEC);
  // putstring(", type is FAT");
  // Serial.println(myBrobot.vol.fatType(),DEC);     // FAT16 or FAT32?

  // // Try to open the root directory
  // if (!myBrobot.root.openRoot(myBrobot.vol)) {
  //   putstring_nl("Can't open root dir!"); // Something went wrong,
  //   while(1);                             // then 'halt' - do nothing!
  // }
  // Initialize all of Brobot's public variables
  myBrobot.incomingByte = -1;
  myBrobot.currentPanAngle = 90;
  myBrobot.currentTiltAngle = 90;
  myBrobot.nextPanAngle = 90;
  myBrobot.nextTiltAngle = 90;
  myBrobot.currentLBAngle = 90;
  myBrobot.currentRBAngle = 90;
  myBrobot.neckTimer = 400;
  myBrobot.neckSpeed = NECK_SPEED;
  myBrobot.headMoveToggle = 0;
  myBrobot.leftToggle = 0;
  myBrobot.rightToggle = 0;
  myBrobot.upToggle = 0;
  myBrobot.downToggle = 0;

  // Run Brobot setup function (initializes LED eyes)
  myBrobot.setup();

  // Attach and initialize all 4 servos
  myBrobot.pan.attach(panPin);
  myBrobot.tilt.attach(tiltPin);
  myBrobot.leftBrow.attach(leftBrowPin);
  myBrobot.rightBrow.attach(rightBrowPin);
  myBrobot.pan.write(myBrobot.currentPanAngle);
  delay(20);
  myBrobot.tilt.write(myBrobot.currentTiltAngle);
  myBrobot.leftBrow.write(myBrobot.currentLBAngle);
  myBrobot.rightBrow.write(myBrobot.currentRBAngle);
  //SoftwareServo::refresh();
  delay(20);


  myBrobot.updateFace();

  delay(2000);
  SoftwareServo::refresh();
}

void loop() {
  // Every loop check for Bluetooth data
  myBrobot.checkBT();

  // The following code sets Brobot's eyebrow positions
  //  - -
  if (myBrobot.nextEmotion == NEUTRAL) {
    //myBrobot.togglePause = true;
    myBrobot.nextLBAngle = 90;
    myBrobot.nextRBAngle = 90;
    while ((myBrobot.currentLBAngle != myBrobot.nextLBAngle) || (myBrobot.currentRBAngle != myBrobot.nextRBAngle)) {
      if (myBrobot.currentLBAngle < myBrobot.nextLBAngle) {
        myBrobot.currentLBAngle++;
      } else if (myBrobot.currentLBAngle > myBrobot.nextLBAngle) {
        myBrobot.currentLBAngle--;
      }
      if (myBrobot.currentRBAngle < myBrobot.nextRBAngle) {
        myBrobot.currentRBAngle++;
      } else if (myBrobot.currentRBAngle > myBrobot.nextRBAngle) {
        myBrobot.currentRBAngle--;
      }
      myBrobot.leftBrow.write(myBrobot.currentLBAngle);
      myBrobot.rightBrow.write(myBrobot.currentRBAngle);
      SoftwareServo::refresh();
    }
    // if((myBrobot.currentLBAngle == myBrobot.nextLBAngle) && (myBrobot.currentRBAngle == myBrobot.nextRBAngle)){
    //   myBrobot.togglePause = false;
    // }
  }

  //  /
  else if (myBrobot.nextEmotion == SURPRISED || myBrobot.nextEmotion == HAPPY || myBrobot.nextEmotion == SAD || myBrobot.nextEmotion == LOVE) {
    //myBrobot.togglePause = true;
    myBrobot.nextLBAngle = 120;
    myBrobot.nextRBAngle = 60;
    while ((myBrobot.currentLBAngle != myBrobot.nextLBAngle) || (myBrobot.currentRBAngle != myBrobot.nextRBAngle)) {
      if (myBrobot.currentLBAngle < myBrobot.nextLBAngle) {
        myBrobot.currentLBAngle++;
      } else if (myBrobot.currentLBAngle > myBrobot.nextLBAngle) {
        myBrobot.currentLBAngle--;
      }
      if (myBrobot.currentRBAngle < myBrobot.nextRBAngle) {
        myBrobot.currentLBAngle++;
      } else if (myBrobot.currentRBAngle > myBrobot.nextRBAngle) {
        myBrobot.currentRBAngle--;
      }
      myBrobot.leftBrow.write(myBrobot.currentLBAngle);
      myBrobot.rightBrow.write(myBrobot.currentRBAngle);
      SoftwareServo::refresh();
    }
    // if ((myBrobot.currentLBAngle == myBrobot.nextLBAngle) && (myBrobot.currentRBAngle == myBrobot.nextRBAngle)) {
    //   myBrobot.togglePause = false;
    // }
  }
 
  else if (myBrobot.nextEmotion == ANGRY) {
    //myBrobot.togglePause = true;
    myBrobot.nextLBAngle = 60;
    myBrobot.nextRBAngle = 120;
    while ((myBrobot.currentLBAngle != myBrobot.nextLBAngle) || (myBrobot.currentRBAngle != myBrobot.nextRBAngle)) {
      if (myBrobot.currentLBAngle < myBrobot.nextLBAngle) {
        myBrobot.currentLBAngle++;
      } else if (myBrobot.currentLBAngle > myBrobot.nextLBAngle) {
        myBrobot.currentLBAngle--;
      }
      if (myBrobot.currentRBAngle < myBrobot.nextRBAngle) {
        myBrobot.currentRBAngle++;
      } else if (myBrobot.currentRBAngle > myBrobot.nextRBAngle) {
        myBrobot.currentRBAngle--;
      }
      myBrobot.leftBrow.write(myBrobot.currentLBAngle);
      myBrobot.rightBrow.write(myBrobot.currentRBAngle);
      SoftwareServo::refresh();
    }
    //if((myBrobot.currentLBAngle == myBrobot.nextLBAngle) && (myBrobot.currentRBAngle == myBrobot.nextRBAngle)){
    //   myBrobot.togglePause = false;
    //}
  }
  SoftwareServo::refresh();
  // Update Brobot's face each loop

  myBrobot.updateFace();

  /* The following code controls the pan/tilt neck servos
  // Brobot will randomly look in a defined set of angles for both pan and tilt.
  // Each loop, if the current servo position variable is not at the same position 
  // as the next position variable, the servos will increment/decrement the current 
  // angle by 1 as needed. The neckSpeed variable causes the pan/tilt servos to only 
  // change every *neckspeed* loop cycle. The neckTimer variable causes Brobot to pause
  // before looking in another direction.
  */

  if (myBrobot.headMoveToggle == 0) {
    if (myBrobot.currentPanAngle == myBrobot.nextPanAngle) {
      if (myBrobot.neckTimer == 0) {
        myBrobot.nextPanAngle = random(MIN_PAN_ANGLE, MAX_PAN_ANGLE);
        myBrobot.nextTiltAngle = random(MIN_TILT_ANGLE, MAX_TILT_ANGLE);
        Serial.println(myBrobot.nextPanAngle);
        Serial.println(myBrobot.nextTiltAngle);
        Serial.println("under tilt angle");
      } else {
        myBrobot.neckTimer--;
      }
    } else {
      myBrobot.neckSpeed--;
      myBrobot.neckTimer = random(60, 80);
      if (myBrobot.neckSpeed == 0) {
        if (millis() % 2 == 0) {
          if (myBrobot.currentPanAngle < myBrobot.nextPanAngle) {
            myBrobot.currentPanAngle++;
          } else if (myBrobot.currentPanAngle > myBrobot.nextPanAngle) {
            myBrobot.currentPanAngle--;
          }
          myBrobot.pan.write(myBrobot.currentPanAngle);
          SoftwareServo::refresh();
          //delay(10);
        } else {
          if (myBrobot.currentTiltAngle < myBrobot.nextTiltAngle) {
            myBrobot.currentTiltAngle++;
          } else if (myBrobot.currentTiltAngle > myBrobot.nextTiltAngle) {
            myBrobot.currentTiltAngle--;
          }
          myBrobot.tilt.write(myBrobot.currentTiltAngle);
          SoftwareServo::refresh();
        }
        myBrobot.neckSpeed = NECK_SPEED;
      }
    }
  } else {
    myBrobot.neckSpeed--;
    if (myBrobot.neckSpeed == 0) {
      if (myBrobot.currentTiltAngle <= MAX_TILT_ANGLE) {
        if (myBrobot.upToggle) {
          myBrobot.currentTiltAngle++;
        }
      }
      if (myBrobot.currentTiltAngle >= MIN_TILT_ANGLE) {
        if (myBrobot.downToggle) {
          myBrobot.currentTiltAngle--;
        }
      }
      if (myBrobot.currentPanAngle <= MAX_PAN_ANGLE) {
        if (myBrobot.rightToggle) {
          myBrobot.currentPanAngle++;
        }
      }
      if (myBrobot.currentPanAngle >= MIN_PAN_ANGLE) {
        if (myBrobot.leftToggle) {
          myBrobot.currentPanAngle--;
        }
      }
      myBrobot.pan.write(myBrobot.currentPanAngle);
      myBrobot.tilt.write(myBrobot.currentTiltAngle);
      SoftwareServo::refresh();
      delay(10);
      myBrobot.neckSpeed = NECK_SPEED;
    }
  }

  if (myBrobot.soundToggle && !myBrobot.togglePause) {
    SoftwareServo::refresh();
    //delay(200);
    myBrobot.playComplete();
  }
  //delay(20);
}

```
<!--- 
# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 
-->
# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Uno | programmable microcontroller board | $28.50 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Adafruit wave shield | adding audio | $26.82 | <a href="https://www.amazon.com/Adafruit-Wave-Shield-Arduino-Kit/dp/B00IQXZN9Q/"> Link </a> |
| 2x 8x8 LED Matrixes | display as eyes | $7.99 | <a href="https://www.amazon.com/DIYables-Display-Arduino-ESP8266-Raspberry/dp/B0BXKM66XX/"> Link </a> |
| 16x2 LCD Character Display w/ I2C backpack | display messages | $8.99 | <a href="https://www.amazon.com/SunFounder-Serial-Module-Display-Arduino/dp/B071Y6JX3H/"> Link </a> |
| 2x MG995 Servo Motor | pan and tilt head | $18.99 | <a href="https://www.amazon.com/180%C2%B0High-Torque-Helicopter-Airplane-Futaba/dp/B07PFD6H31/"> Link </a> |
| Pan Tilt Servo Brackets | making multi axis joints | $6.43 | <a href="https://www.amazon.com/Bracket-Sensor-Multifunction-Bearing-Screws/dp/B0B3Y7ZXZD/"> Link </a> |
| HC-SR04 Ultrasonic Sensor | Track distance | $1.80 | <a href="https://www.amazon.com/Organizer-Ultrasonic-Distance-MEGA2560-ElecRight/dp/B07RGB4W8V/"> Link </a> |
| 2 Watt 8 Ohm Small Speaker | Output for audio | $3.94 | <a href="https://www.amazon.com/Gikfun-Speaker-Diameter-Arduino-AE1054/dp/B01EJI8UWI/"> Link </a> |
| 4 AA Battery Holder with Vdd and Gnd Wires | power source | $3.24 | <a href="https://www.amazon.com/LAMPVPATH-Battery-Holder-Leads-Wires/dp/B07T7MTRZX/"> Link </a> |
| 2x SG90 9G Micro Servos | move eyebrows | $7.29 | <a href="https://www.amazon.com/Sipytoph-Helicopter-Airplane-Walking-Control/dp/B09185SC1W/"> Link </a> |
| 40p 200mm Male-to-Female Dupont Cables | interconnect components | $3.25 | <a href="https://www.amazon.com/GenBasic-Solderless-Dupont-Compatible-Breadboard-Prototyping/dp/B01L5UKAPI/"> Link </a> |
| 40p 200mm Female-to_Male Jumper Cables | connect electric circuits to circuit boards | $12.49 | <a href="https://www.amazon.com/uxcell-Female-Jumper-2-54mm-Breadboard/dp/B07GN85RC2/"> Link </a> |
| 8 GB microSDHC Class 4 Flash Memory Card SDC4/8GBET | insert into wave shield | $9.99   | <a href="https://www.amazon.com/Kingston-Class-MicroSDHC-Memory-Adapter/dp/9983039281/"> Link </a> |
| HC-05 Wireless Bluetooth RF Transceiver | connect android device | $10.39 | <a href="https://www.amazon.com/HiLetgo-Wireless-Bluetooth-Transceiver-Arduino/dp/B071YJG8DR/"> Link </a> |
| Breadboard with 2 Power Rails and 50p Jumper Cables | connecting components | $11.99 | <a href="https://www.amazon.com/HUAREW-Breadboard-Jumper-Include-Points/dp/B09VKYLYN7/"> Link </a> |
| 4x 5/8 steel screw | securing components | $0.44 | <a href="https://www.amazon.com/Sentry-Supply-651-0358-8-Inch-Chrome/dp/B00DUQ9NK4/"> Link </a> |
| 8x 4-40x3/4 steel screw | securing components | $0.56 | <a href="https://www.amazon.com/Phillips-Machine-Screws-Stainless-Thread/dp/B01HQ6UP32/"> Link </a> |
| 12x 4-40x1/2 steel screw | securing components | $0.27 | <a href="https://www.amazon.com/2500pcs-4-40x1-Socket-Button-Stainless/dp/B06XF1W9TQ/"> Link </a> |
| 20x 4-40 steel nut | securing components | $0.40 | <a href="https://www.amazon.com/Steel-Hex-4-40-Threads-Pack/dp/B000N2YSU8/"> Link </a> |
| 4x 6-32x1/2 oval | securing components | $0.29 | <a href="https://www.amazon.com/Prime-Line-Products-MP9191-Construction-Slotted/dp/B01MA6EMXH/"> Link </a> |
| 4x 6-32 nut | securing components | $0.64 | <a href="https://www.amazon.com/Instockbolts-Nylon-Insert-Stainless-Steel/dp/B09V4T41WL/"> Link </a> |

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
