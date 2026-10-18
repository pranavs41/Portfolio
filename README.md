# Pranav Shivashankar — Engineering Portfolio

B.S. Electrical and Computer Engineering, UT Austin

**[Full portfolio (PDF)](Pranav_Shivashankar_Portfolio.pdf)**

- **Swarm Drone Flight Controller** — Texas Aerial Robotics, lead hardware.
  36 x 39 mm 4-layer PCB, chip-down ESP32-S3, buck + LDO power tree,
  ICM-42688-P, BMP581, MAX-M10S GPS. KiCad 9.
- **VTOL Quadplane Flight Controller** — 74 x 66 mm 4-layer PCB around an
  STM32H743 with an ArduPilot pin map: two dissimilar IMUs, dual barometers,
  CAN, microSD, 14 Pixhawk-pinout JST-GH ports, 6S power path. Schematic
  generated from Python, KiCad run headless through routing, checks and the
  JLCPCB fab package.
- **Custom FPV Quadcopter** — ESP32 flight controller written from scratch.
  500 Hz cascaded PID, DShot300 via RMT, tiered failsafe.
  1.50° RMS hover error measured from logged telemetry.
- **Embedded Game Console** — TI MSPM0G3507, custom 4-layer PCB,
  ARM assembly and C, schematic capture through board bring-up.
- **Gesture-Control Glove** — ESP32, BNO085 IMU, BLE HID and ESP-NOW.
- **FridgeGuard** — 3rd place, UT IEEE Techathon.
- **Custom Macropad** — KiCad, ATmega32U4, QMK.

pranavshivashankar12@gmail.com
