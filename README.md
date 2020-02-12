# iot-candysorter
## General Info
This was (actually still developing this) a school project on an experimental IoT-course.
Team members: Harri Nupponen, Valtteri Nummi, Topi Nummi
## Ingredients
- ESP32 (Node MCU)
- TCS34725 Color Sensor
- Servo
- Arduino IDE
- Blynk-app for the UI

## How it works
- You can choose red, green and blue candies from the UI. Amount between 0-5 each.
- The color sensor detects the rgb-values
- The servo directs the "ordered" candies to the other side and the "non-ordered" candies to the other side.

Check out the video (In finnish. Order is 1 red, 2 greens and 3 blues, according to the UI-image below):
https://youtu.be/FscnV3nYT_Y

## The UI
![CS-UI](https://github.com/Intomies/iot-candysorter/blob/master/img/cs-ui2.png "CS-UI")
