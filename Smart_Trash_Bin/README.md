# Smart Powered Trash Bin 🤖♻️

---

The smart trash bin works by first detecting a hand in front of the sensor. Then the system works by clicking 1 out of 4 buttons (red for aluminum, blue for glass, yellow for general and black for pvc) and the plate rotates based on the input of the buttons to the right compartment. The Kypruino board commands a servo motor attached to the lid to open it automatically, while simultaneously updating a 0.91″ OLED screen connected to the board to display the detected material. The waste falls onto a rotating plate, which turns toward the correct compartment. There are four subdivided bins inside the main container (Glass, Aluminium, PVC, General Waste). The plate lowers, drops the waste into the selected bin, and returns to its original position. A companion web app connects to the smart bins and provides monitoring and gamification features. The app shows the fill percentage of each bin and sends a notification when they are full and need emptying. The web app also includes a gamified recycling system where users create profiles, track their recycling activity, and earn points for recycling different materials. Users can gain levels, unlock badges, and appear on leaderboards based on how much they recycle.
The app also includes an interactive map of Cyprus showing the locations of all smart recycling bins so users can easily find the nearest one. Users can participate in daily recycling challenges, tournaments, and competitions with friends, schools, or cities. The system tracks statistics such as total recycled weight, materials sorted, and environmental impact, making recycling more engaging and competitive while encouraging responsible waste management.
---
- 🔴 Red → Aluminum  
- 🔵 Blue → Glass
- 🟡 Yellow → General 
- ⚫ Black → PVC 

---

## 🔧 Key Features
- Motion detection and automatic lid operation
- Material selection and sorting logic via buttons
- Microcontroller control
- Modular and Futuristic

---  

## 🛠 Technologies Used
- Microcontroller: Kypruino / Arduino
- Programming Languages: C++
- Hardware: Ultrasonic sensor, servo motor, OLED display, buttons
- Other Tools: Companion mobile app for bin monitoring

---

## 🎯 Objective
Make the world a more enviromentally friendly place for all of us and reduce global waste ♻️

---

## 📁 Project Structure
- `/code` → https://github.com/achilleaschristou/Tech_Portfolio/blob/main/Smart_Trash_Bin/Code.txt

---

## 💡 Future Improvements

- Self-Cleaning Mechanism with a simple wiping or UV sterilization system to keep bins hygienic 🧼
- Solar-Powered Operation by making it energy-efficient and integrating a small solar panel to power sensors and motors ☀️
- Voice Control & Smart Home Integration to allow opening/closing via voice commands or integrate with Google Home / Alexa 🎙️🏠

---

## 💻 Tech Stack:

![Arduino](https://img.shields.io/badge/Arduino-%23007396.svg?style=for-the-badge&logo=arduino&logoColor=white) 
![Kypruino](https://img.shields.io/badge/Kypruino-%23FF9900.svg?style=for-the-badge&logo=arduino&logoColor=white)  ![Servo Motors](https://img.shields.io/badge/Servo_Motors-%23FF6600.svg?style=for-the-badge)  
![Ultrasonic Sensor](https://img.shields.io/badge/Ultrasonic_Sensor-%2300CCFF.svg?style=for-the-badge)  ![OLED Display](https://img.shields.io/badge/OLED_Display-%23000000.svg?style=for-the-badge&logo=adobe&logoColor=white)   
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Mobile App](https://img.shields.io/badge/Mobile_App-%23FFCC00.svg?style=for-the-badge)  
 
---

## 🚀 Notes

Created as an independent engineering project, it seeks to solve problems, improve efficiency, and implement smart automation.
