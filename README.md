The ISS Orbital Tracker Workshop will guide attendees through assembling an automated robotic pointer that tracks the location of the International Space Station in real time. The workshop will be divided into two parts. Part 1 covers the science behind orbital mechanics, and gives background on the project itself. Part 2 is a hands-on section where attendees are provided with the materials to build their own orbital pointer, and are guided through assembly and programming of the device.
<br><br><br><br><br><br><br><br><br>
Prepared by Salvador Vasquez
<div style="page-break-after: always"></div>


# Lecture

## Part 1: Orbits

- ISS
- Orbits
	- Keplerian vs real life
- SGP4

## Part 2: Pointer

### Hardware
- ESP8266
- Stepper motor
	- Driver
- Servomotor

### Software
- SGP4
	- Orbital math
	- Coordinate systems
- Azimuth: Stepper
- Elevation: Servo
- Updating TLE
	- From internet: [Link](https://www.celestrak.org/NORAD/elements/gp.php?CATNR=25544&FORMAT=TLE)
	- By hand
	- Tracking different satellites

<div style="page-break-after: always"></div>


# Budget

| Item | Description     | Cost   | Link |
|------|-----------------|--------|------|
| 1    | ESP8266         | $2.83  | [Link](https://share.temu.com/dwIEmbCtYWA) |
| 2    | Stepper         | $0.61  | [Link](https://www.aliexpress.us/item/3256804755489791.html) |
| 3    | Servo           | $1.22  | [Link](https://www.aliexpress.us/item/3256804364197715.html) |
| 4    | Stepper Driver  | $0.64  | [Link](https://www.digikey.com/short/zwjfqjd0) |
| 5    | Slip Ring       | $2.57  | [Link](https://www.aliexpress.us/item/3256802527929967.html) |
| 6    | Micro USB cable | $0.86  | [Link](https://share.temu.com/fXmrZp8YbyA) |
| 7    |  5W power brick | $1.49  | [Link](https://share.temu.com/9dzaBk76MuA) |
| 8    | PCB             | ~$2.00  | [Link](https://www.flux.ai/vsalvador/pointer?editor=schematic) |
|      | Total           | $12.50 |


# Resources
[Orbital Mechanics Tutorials](http://celestrak.org/columns/)
[SGP4 Academic paper](https://celestrak.org/publications/AIAA/2008-6770/AIAA-2008-6770.pdf)
[Original source code in C++](https://github.com/gradyh/ISS-Tracking-Pointer/tree/master)
[NORAD Satellite Data](https://celestrak.org/NORAD/elements/)

![[1_dYa0T_eg6DZa03Hv9OHaCw.webp]]

<div style="page-break-after: always"></div>


# Updates
- Found cheaper slip ring
- Added PCB
- ~~Changed RPi Pico W for ESP8266~~
- ~~Added USB cable to materials~~
- ~~Added more info on TLE section~~
