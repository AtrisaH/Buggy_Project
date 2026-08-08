# Buggy Project | Arduino DFPlayer Feature

## Project Overview
This project was completed as a coursework for my module, where students were required to design, build, and demonstrate a fully functional remote‑controlled buggy car. Circuit design, construction quality, creativity, additional electrical features, and the buggy's overall performance during a driving competition were the main areas of evaluation.

Our team built the buggy base using the provided BTLE remote control system by our module and designed our own twin H‑bridge motor driver using components. We added an Arduino‑based audio system using the DFPlayer Mini MP3 module for our additional feature on our buggy. This system was designed and implemented by me.

## DFPlayer Mini Audio System
We added a secondary processor (Arduino) to control a DFPlayer Mini MP3 module to enhance our buggy's creativity and user interactivity. As a result the buggy was able to play:
- Background audio and music
- A Horn sound  
- Obstacle warning beep (sensor) 

The Arduino interfaced with:
- A horn button  
- The ultrasonic sensor  
- The custom H‑bridge motor driver  
- The DFPlayer Mini 

##  Development Code
The code file contains scripts developed during the building process, alongside the final code:
1. **Board diagnostic test**  
2. **Motor GPIO test**  
3. **Raw DFPlayer serial command test**  
4. **DFPlayer library test**  
5. **Horn button test**  
6. **Final integrated system**  
   - Background music loop (start/pause using a button)
   - Horn button  
   - Ultrasonic obstacle warning  

These scripts were created during the development to test the Arduino before reaching a final code.

## Hardware used
- Arduino Uno  
- DFPlayer Mini MP3 module  
- HC‑SR04 ultrasonic sensor  
- Custom twin H‑bridge motor driver   
- BTLE remote control system (provided in module)  
- Speaker (3W)  
- Push button (horn)  
- Battery pack  


## Final Prototype
A photo of the completed buggy is included in the `images/` folder.

## Notes
- The 6-stage test file showcases the actual code progression used to build and verify the audio and sensor system, resulting in the final integrated version that ran on the         buggy (background music, horn, and ultrasonic sensor + warning). The wheels control was handled separately via the provided H-bridge and BTLE remote system, not by the Arduino.
- The codes in this repository represents draft and test scripts used during development.
- The Arduino system was individually assessed as First Class work within the group project. 

