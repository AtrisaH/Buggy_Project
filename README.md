# ELEC1801 Buggy Project – Arduino DFPlayer Feature

## Project Overview
This project was completed as part of the ELEC1801 module, where students were required to design, build, and demonstrate a fully functional remote‑controlled buggy. The assessment focused on circuit design, build quality, creativity, additional electronic features, and the buggy’s performance during a driving test.

Our group constructed the buggy platform using the provided BTLE remote control system and designed our own twin H‑bridge motor driver using discrete components, as required by the brief. To enhance the buggy’s features, we integrated an Arduino‑based audio system using the DFPlayer Mini MP3 module.

## Added Feature: DFPlayer Mini Audio System
To enhance the buggy’s interactivity and creativity, we added a secondary processor (Arduino) to control a DFPlayer Mini MP3 module. This allowed the buggy to play:
- Background engine audio  
- Horn sound  
- Obstacle warning beep  

The Arduino was powered independently and interfaced with:
- A horn button  
- The ultrasonic sensor  
- The custom H‑bridge motor driver  
- The DFPlayer Mini (via SoftwareSerial)

##  Development Code
The code file contains staged development scripts used during the build:
1. **Board diagnostic test**  
2. **Motor GPIO test**  
3. **Raw DFPlayer serial command test**  
4. **DFPlayer library test**  
5. **Horn button test**  
6. **Final integrated system**  
   - Background music loop  
   - Horn button  
   - Ultrasonic obstacle warning  

These scripts were used to verify each subsystem before full integration.

## Hardware Summary
- Arduino Uno / Nano  
- DFPlayer Mini MP3 module  
- HC‑SR04 ultrasonic sensor  
- Custom twin H‑bridge motor driver (discrete components)  
- BTLE remote control system (provided in module)  
- Speaker (3W)  
- Push button (horn)  
- Battery pack  


## Final Prototype
A photo of the completed buggy is included in the `images/` folder.

## Notes
- The final working code was implemented directly on the hardware during testing and demonstration.
- The code in this repository represents draft and subsystem test scripts used during development.

