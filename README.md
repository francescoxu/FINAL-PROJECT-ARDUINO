# FINAL-PROJECT-ARDUINO

##Introduction

For my project I used the 8x8 RGB LED matrix named WS2811, The reason for my choice it's because I liked the idea of using it to create animations and characters. After I watched some videos on youtube, I was sure that it was going to be my final project. I bought three WS2811 and some wires. The purpose of my project is to create a perpetual animation on the matrix and then create a case to put it in and cover it with an acrylic sheet, so I can put in my room.



PROCESS
-

First of all I needed to obtain the materials, since I can't go out during this period, I searched on amazon I found the WS2811 and I bought three of them, then I got the jumping wires on amazon too.

Then I did a research on how to setup the LED matrix, as a result I downloaded an arduino library to control these RGB LED, named FastLED.h. This library is used to efficently controlling the LED. After learning how control the matrix I started playing around. 
Then my first sketch is copied from a GIF of Mario&Luigi found on the web.
![Marioandluigi](https://user-images.githubusercontent.com/56677617/84087796-3338f180-a9eb-11ea-9194-bc2825469277.gif)

I used microsoft excel to simplify my coding on arduino, because I can find the LED postion (or pixel) in an easier way.

<img width="1609" alt="Screen Shot 2020-06-09 at 12 53 01 AM" src="https://user-images.githubusercontent.com/56677617/84088064-ef92b780-a9eb-11ea-9556-befcd2a870e3.png">

I copied every pixel of the GIF in an 8x8 excel sheet until I made every frame of it.
Since it was my first sketch I turn on every LED myself on the code without using the simple method of array.

<img width="844" alt="Screenshot 2020-06-09 at 00 57 58" src="https://user-images.githubusercontent.com/56677617/84088335-924b3600-a9ec-11ea-9e11-5ea22added91.png">

I found out that covering the LED with a piece of paper makes it look better:
![IMG_5787](https://user-images.githubusercontent.com/56677617/84089348-04bd1580-a9ef-11ea-84d6-286c3caef188.JPG)





But the result was very satisfying it turns out to be the exact same as the GIF. That made me happy and excited about working with LED matrix.

After searching for 8x8 characters online, I found out that is hard to make good characters with only 64 LED, 16x16 size for the characters would have been perfect just like the good old pixelated game.

These are two characters I copied from the web:

<img width="900" alt="Screen Shot 2020-06-09 at 1 12 18 AM" src="https://user-images.githubusercontent.com/56677617/84089135-85c7dd00-a9ee-11ea-805d-b4fe798394de.png">

These are the result on the LED matrix:

<img width="1102" alt="Screen Shot 2020-06-09 at 1 22 23 AM" src="https://user-images.githubusercontent.com/56677617/84089781-2bc81700-a9f0-11ea-9018-8b3e18091d79.png">

<img width="899" alt="Screen Shot 2020-06-09 at 1 36 35 AM" src="https://user-images.githubusercontent.com/56677617/84090311-b6f5dc80-a9f1-11ea-8fe2-dfac217da014.png">

This is the file I used to draw all the sketches, there are two sheets:

[8x8ArduinoProject.xlsx](https://github.com/francescoxu/FINAL-PROJECT-ARDUINO/files/4749104/8x8ArduinoProject.xlsx)

While doing the animation of Captain america vs Iron man I found out that using array will makes my work easier.
So first of all I create an array for let's say the blue part of the suit of captain america.
Instead of writing every leds of it like this:
leds[1] = CRGB::Blue;
leds[2] = CRGB::Blue;
etc...

I put them all in an array:
int Bsuit[] = {1,2,10,11,12,13,14,25,26,27}

then in void loop()
use the for loops to go through all the array value and set the color to blue:
for ( int i = 0; i < 10; i++) {
   leds[Bsuit[i]] = CRGB::Blue;
   }
(While I was writing this code, I sadly remembered that I could use .lenthg to find the array length instead of counting..)

While doing the animation of Captain america vs Iron man I found out that using array will makes my work easier.
So first of all I create an array for let's say the blue part of the suit of captain america.
Instead of writing every leds of it like this:

```
leds[1] = CRGB::Blue;
leds[2] = CRGB::Blue;
leds..........
......
```

I put them all in an array:

`int Bsuit[] = {1,2,10,11,12,13,14,25,26,27}`

then in void loop()

use the **for** loops to go through all the array value and set the color to blue:

```
for ( int i = 0; i < 10; i++) {
   leds[Bsuit[i]] = CRGB::Blue;
   }
```

_(While I was writing this code, I sadly remembered that I could use .lenthg to find the array length instead of counting..)_

Here's a sneak peek of the code:
<img width="1440" alt="Screenshot 2020-06-09 at 01 48 49" src="https://user-images.githubusercontent.com/56677617/84090997-89119780-a9f3-11ea-8f33-863de4c02e99.png">

A photo of my project:
<img width="1629" alt="Screen Shot 2020-06-09 at 1 52 27 AM" src="https://user-images.githubusercontent.com/56677617/84091172-f8878700-a9f3-11ea-92c3-7a028cd68092.png">

It was very fun working with LED matrixes, I learnt a lot. I hope one day I can put them on my room with a nice case and proudly say that I didn't buy that, but I made it myself.


