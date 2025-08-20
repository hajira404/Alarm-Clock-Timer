# Alarm Clock & Timer in C++

## Overview
This project contains two simple C++ console-based applications:

- **Alarm Clock** → User enters a future alarm time (in 24-hour format). The program calculates the difference from the current time, displays a live countdown, and buzzes when the time is reached.  
- **Timer** → User sets an alarm by specifying hours, minutes, and seconds. The program waits until the system clock matches the input and then rings the alarm.

---

## Features
- Accepts time in 24-hour format.  
- Displays countdown of minutes and seconds remaining.  
- Final 60-second countdown before ringing.  
- Produces a beep (`sound()`) when the alarm goes off.  
- Simple terminal interface with live updates.  

---

## Technologies Used
- **Language**: C++ (Turbo C++ style)  
- **Libraries**: `<iostream.h>`, `<conio.h>`, `<dos.h>`, `<time.h>`  
- **Concepts**: Time calculation, loops, system delays, inheritance in OOP (for Timer).  

---

## How to Run
1. Compile with **Turbo C++ / Borland C++** (because `conio.h` & `dos.h` are compiler-specific).  
2. Run the executable.  
3. Enter the required alarm/timer values.  
4. Wait for the buzzer 🎵  

---

## Learning Highlights
- Worked with **system time** in C++.  
- Practiced **OOP concepts** (Timer class with inheritance).  
- Hands-on with **low-level system functions** (`sound()`, `delay()`, `clrscr()`).  
- Built a **real-time interactive console app**.  
