##### *ABOUT*:
Hi 👋, I am **fFlorian**, embedded engineer/ maker with a formal education in Mechatronics. I'm intereseted in:
- developing embedded solutions that connect the physical world with software logic
- low level programming in C,C++
- designing prototype parts for 3D printing
- electronics and PCB design.
- cool sensors for collecting IOT data
- precision agriculture or process monitoring/ automation

The tagline for my embedded goals would be something like:

Do as much with as little as possible.

##### *CONTACT*:

Email:      [fflori4n@gmail.com](mailto:fflori4n@gmail.com)</br>
Website:    [fflori4n.com](fflori4n.com)</br>
Github:     [github.com/fflori4n](https://github.com/fflori4n)</br>
Grabcad:    [grabcad.com/florian.f-4](https://grabcad.com/florian.f-4)

##### *PROGRAMMING LANGUAGES*:
<div>
<a href="https://www.cprogramming.com/" title="C programming language">
<img src="assets/devicons/c-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://cppreference.com/" title="C++">
<img src="assets/devicons/cplusplus-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://www.python.org/" title="Python programming language (as opposed to python the snake, or the guy from mythology)">
<img src="assets/devicons/python-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://www.gnu.org/" title="Linux based operating systems">
<img src="assets/devicons/linux-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://www.arduino.cc/" title="Arduino">
<img src="assets/devicons/arduino-original-wordmark.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://en.wikipedia.org/wiki/PowerShell" title="Power shell">
<img src="assets/devicons/powershell-plain.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://git-scm.com/" title="Git">
<img src="assets/devicons/git-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://opencv.org/" title="Open CV">
<img src="assets/devicons/opencv-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://grafana.com/" title="Grafana">
<img src="assets/devicons/grafana-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://www.influxdata.com/" title="Influx db">
<img src="assets/devicons/influxdb-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://www.atlassian.com/software/jira" title="Jira">
<img src="assets/devicons/jira-original.svg" alt="\" style="width: auto; height:3em;">
</a>
<a href="https://flutter.dev/" title="Flutter">
<img src="assets/devicons/flutter-original.svg" alt="\" style="width: auto; height:3em;">
</a>
</br>
</br>
</div>

## *PROJECT PORTFOLIO:*
*Let me show you some *COOL* projects I worked on:*
</br>

### **nod3-comfirm** - *Common firmware for ESP32 based devices*
**`C++20` `ESP_IDF` `ESP32_C3`**

Written using ESP_IDF and modern(ish) C++, nod3-comfirm aims to be used as a basic firmware for all my smart sensor devices. Firmware has basic functions that are needed for every IoT thing, like:
- Network management (WLAN)
- IO Control
- ADC continous/ DMA and other ADC functions
- Time keeping, NTP and RTC functions
- Websocket communication with Homeassistant custom component
- libraries for common sensors using I2C

https://github.com/fflori4n/nod3-comfirm
##
### IoT wind and rain sensors
**`ESP-Arduino` `websockets` `ESP32_S3`**

The classic maker project of a 'wheather station' basically. Measuring wind speed, wind angle and rainfall. The sensors are fully 3D printed. Sensor connects to Homeassistant via websocket and custom component, this was written in Arduino framework using ESP32-S3, the sensors are now also supported in nod3-confirm, so the next version will be battery/solar + ESP C3.

<p align="center">
<img src="assets/pics/szeltekero.png" alt="wind rain sens architecture" style="width: 29.3%; height:auto;">
<img src="assets/pics/wind_sens.png" alt="wind sensor" style="width: 31%; height:auto;">
<img src="assets/pics/rain_sens1.png" alt="wind sensor" style="width: 31%; height:auto;">
</p>

##
### **OPEN hand** - *hand partial prosthetic*
**`mechanical design` `motor positioning` `robotics`**

Working in a team of four engineers to build a prototype 3D printed partial hand prosthesis. To prove that a prosthesis does not have to cost a lot of money to be actually useful, and can easily be built using tech available to makers.

Read more about the goals and challenges on the project's github page: https://github.com/AleksaHeler/OpenHand

<p align="center">
<img src="assets/pics/AleksaHeler_OpenHand_OpenHand_built.jpg" alt="linear motor - open hand" style="width: 93%; height:auto;">
</p>

<details>
  <summary>Details</summary>

  
  <p align="center">
    <img src="assets/pics/linear_motor.png" alt="linear motor - open hand" style="width: 42.5%; height:auto;">
    <img src="assets/pics/hall_feedback_pattern.png" alt="hall feedback pattern - open hand" style="width: 38.5%; height:auto;">
    </p>
    <p align="center">
    <img src="assets/pics/hand_V07.png" alt="hand07 - open hand" style="width: 40%; height:auto;">
    <img src="assets/pics/fingerV2.png" alt="hand2 - open hand" style="width: 40%; height:auto;">
  </p>
</details>

##
### **Smart Hive** - *Smart sensor system for monitoring bee hives - MSC final project*
**`SIM7000G` `RS485` `MQTT` `solar power` `ESP32_Wroom_32_u` `Atmega168` `Atmega328`**

Embedded (Arduino based) sensors for measuring temperature, humidity, ambient light and hive weight. These values are measured, forwarded to a Gateway device over RS485. Gateway device aggregates data from sensors and forwards it to the smart hive server via an LTE/4G mobile modem using MQTT or websockets.

*Repo:* https://github.com/fflori4n/smartHive

<p align="center">
<img src="assets/pics/BHS_all_sensors_00.JPG" alt="BHS sensor - smart hive" style="width: 93%; height:auto;">
</p>
<p align="center">
<img src="assets/pics/hives.png" alt="hives - smart hive" style="width: 42%; height:auto;">
<img src="assets/pics/DHT_sensor_in_hive_av0.png" alt="DHT in hive - smart hive" style="width: 47%; height:auto;">
</p>

<details>
  <summary>More pictures</summary>

<p align="center">
<img src="assets/pics/GW_gateway_board_top.png" alt="Gateway - smart hive" style="width: 30%; height:auto;">
<img src="assets/pics/hive_solar_deploy.png" alt="solar deploy - smart hive" style="width: 45%; height:auto;">
</p>
<p align="center">
<img src="assets/pics/rs485OldScope.png" alt="scope RS485 - smart hive" style="width: 35%; height:auto;">
<img src="assets/pics/smart_hive_grafana.png" alt="scope RS485 - smart hive" style="width: 50%; height:auto;">
</p>

</details>

##
### **Image processing for agricultural drone** 
**`C++14` `python` `RPI4`**

R&D project in collaboration with Drontech ([Drontech Facebook page](https://www.facebook.com/dronteh)) to develop a proof of concept for a device that uses computer vision to estimate plant mass beneath a drone.
A GPIO pin is set to HIGH when plant mass exceeds a defined threshold, the signal is intended to control sprayer valves, turning off pesticide flow when the area under the flight path lacks viable cultivation or the plants have dried out, avoiding unnecessary pesticide use on unproductive areas.

<p align="center">
<img src="assets/pics/drone_plant_detect.gif" alt="rpi flying - drone cam" style="width: 93%; height:auto;">
<img src="assets/pics/rpiFlying.png" alt="rpi flying - drone cam" style="width: 50%; height:auto;">
<img src="assets/pics/rpiDroneCam.jpg" alt="rpi cam - drone cam" style="width: 25%; height:auto;">
</p>

<details>
  <summary>Details</summary>
  </br>
<p align="center">
<img src="assets/pics/droneWGreenLed.png" alt="rpi flying - drone cam" style="width: 25%; height:auto;">
</p>

Developement was done in two stages:
- first a CV algorith was created in python OpenCV based on recorded video footage. The clasification of plants is based only on color and noise/texture. - using YOLO V4 for weed classification was considered but abbadoned due to the limited hardware capabilities, and because it was only a proof of concept.
- after that the computer vision algorithm was rewritten in OpenCV C++ to allow real time processing.

The system runs on a Raspberry Pi 4 using OpenCV C++ for real-time frame processing. Due to limited processing power the frame rate is relatively low (around 15 FPS). For testing purposes, a green LED was connected to the GPIO output (the status of the output is sent also via WiFi telemetry) - and the drone flown over roads, bare land and different kinds of crops and roadside weeds.

*yes, rpi is fixed to the drone using zip ties, and getting absolutely blasted by ground obstacle radar*

</details>

##
### **Liquid level sensing based on capacitance** 
**`ESP web-user interface` `analogue sensor design` `KiCAD`**

This project is more interesting than it is practical. It uses the capacitance of a partially submerged, isolated wire to measure the liquid level inside a water reservoir. While not very precise (±20 mm on a 1400 mm probe if perfectly calibrated), it is a very inexpensive solution that definitely works to a degree. Combine it with an ESP32 and a smartphone, and you have a reservoir level sensor with a web-based readout.

The project repo:
https://github.com/fflori4n/ESP_tankLevelSensor

<p align="center">
<img src="assets/pics/waterLevelSens.png" alt="device readout + web iface - tank level" style="width: 60%; height:auto;">
</p>

<details>
  <summary>Details</summary>
  </br>

<p align="center">
<img src="assets/pics/lm555CapacitiveLevelSens.png" alt="lm555 transducer - tank level" style="width: 50%; height:auto;">
<img src="assets/pics/dielectric.png" alt="lm555 transducer - tank level" style="width: 40%; height:auto;">
</p>

</details>

##
### **3D design and printing**
**`3d-printing` `FDM` `CAD` `CNC`**

3D printing is a great hobby, it allows you to create very complex parts quickly and at a low cost. I have three printers: one MSLA and two FDMs. I mostly use the FDM printers because resin printing is messy, toxic, and relatively expensive for making parts. My main use case is printing technical components. It's also a lot of fun to tinker with the printers, upgrading both the software and hardware to improve print speed or quality.

<p align="center">
<img src="assets/pics/printing_hand_parts.png" alt="printing" style="width: 30%; height:auto;">
<img src="assets/pics/klipper_jank.png" alt="klipper" style="width: 30%; height:auto;">
</p>

**Honorable mention:** A DIY CNC router I built way back, and it has it's own instructable: https://www.instructables.com/CNC-Router-4/

<details>
  <summary>Details</summary>

grabCAD page with some models that are shared for free:
https://grabcad.com/florian.f-4/models

<p align="center">
<img src="assets/pics/anet_a8_working.png" alt="3d anet" style="width: 28%; height:auto;">
<img src="assets/pics/anet_a8.png" alt="3d anet" style="width: 50%; height:auto;">
</p>
<p align="center">
<img src="assets/pics/3dRandomPrints.png" alt="random 3d parts" style="width: 50%; height:auto;">
<img src="assets/pics/slaT5pulley.png" alt="sla pulley" style="width: 25%; height:auto;">
</p>
<p align="center">
<img src="assets/pics/3d_upgrade.png" alt="klipper" style="width: 25%; height:auto;">
</p>

Also at some point, my coffee table was a 3D printer box with 3D printed legs, so that has to count for something I think:
<p align="center">
<img src="assets/pics/coffee_table.png" alt="klipper" style="width: 60%; height:auto;">
</p>

</details>





