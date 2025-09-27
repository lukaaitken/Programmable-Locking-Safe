# Programmable-Locking-Safe

## Overview
This project is a **Digital Controller for a Programmable Locking Safe**, designed and programmed in **VHDL**.  
The safe provides enhanced security features, allowing users to protect their personal belongings with programmable password functionality, alarms, and automated locking mechanisms.

👀 [Watch the Demo Video](https://youtu.be/PupkJDQFcT8)

---

## Project Members
- Luka Aitken  
- Toma Aitken  
- Brandon Breithaupt  

---

## Features
- Password entry using a keypad connected to an FPGA board  
- Support for changing password when needed  
- 7-segment display for user feedback  
- Alarm system that triggers:
  - After 3 incorrect password attempts  
  - If the safe door remains open too long  
- Automatic locking when the door is closed, lock button pressed, or after a timeout  
- LED indicators to show system states:
  - Correct/incorrect password  
  - Door status  
  - Alarm triggered  

---

## Final Design
- The system accepts a **4-digit password**.  
- Users can switch between digits using two toggle switches.  
- If an incorrect password is entered, the alarm will activate.  
- With the correct password, the safe unlocks and starts a timer. If the door is left open too long, the alarm sounds.  
- Closing the door before the timer expires resets the system back to its locked state.  

This final solution creates a secure, interactive, and cost-effective programmable safe.  
