# community_robot_arm MODBUS SUPPORT ADDED

*By default slave ID is set to 2

*List of Registers to Build GCODE Command
  - Holding Register 0 (400001)
    - 0 = G Command
    - 1 = M Command
  - Holding Register 1 (400002)
    - Type of G or M command
  - Holding Register 2 (40003)
    - 0 = positive value for X POS
    - 1 = negative value of X POS
  - Holding Register 3 (400004)
    - X POS Value
  - Holding Register 4 (400005)
    - 0 = positive value for Y POS
    - 1 = negative value of Y POS
  - Holding Register 5 (400006)
    - Y POS Value
  - Holding Register 6 (400007)
    - 0 = positive value for Z POS
    - 1 = negative value of Z POS
  - Holding Register 7 (400008)
    - Z POS Value
  - Holding Register 8 (400009)
    - E POS Value
  - Holding Register 9 (400010)
    - F Speed Value

* Example usage 

[![IMAGE ALT TEXT HERE](https://imgur.com/KoffLor.jpg)]
  - is the equivalent of G0X-40Y100Z80E0F0<br/><br/>
  [![IMAGE ALT TEXT HERE](https://imgur.com/yi6Lf6R.jpg)]
  - is the equivalent of M114<br/><br/>


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/yh1NoQ2Z36A/0.jpg)](https://www.youtube.com/watch?v=yh1NoQ2Z36A)

Community robot arm is an open source collaboration project participated by an online community of learners & developers. It was developed based on the original design by [Florin Tobler](https://www.thingiverse.com/1718984)<br/> with multiple rounds of open hardware & software modification.

**REPOSITORY OF COMMUNITY ROBOT ARM**
* arduino_firmware Version V0.81 (07Aug2021)
  - ESP32 (WEMOS D1R32) SUPPORT WITH WIIMOTE
  - ESP32 JOYSTICK ADJUSTABLE SPEED MULTIPLIER CONFIG
* arduino_firmware Version V0.71 (13Jun2021)
  - ESP32 (WEMOS D1R32) SUPPORT WITH PS4 JOYSTICK OPTIOON
  - CUSTOM SPEED CURVE COMMAND
  - UNO OPTION WITH RAIL
* arduino_firmware Version V0.61 (03May2021)
  - Arduino Uno Controller Option
  - Fixed Issue of G28 Homing for Original Ftobler without endstop
* arduino_firmware Version V0.51 (03Apr2021)
  - Servo Gripper Option
* arduino_firmware Version V0.41 (24Feb2021)
  - Different Lengths of Upper & Lower Shank Supported
* arduino_firmware Version V0.31 (19JAN2021)
  Changes:
  - G92 Current Position Setting Option
  - M114 Endstop State Reporting
  - Limit Checking Move Overflow Prevention
  - Logger Functions
* Arduino Firmware Version V0.21 (28OCT2020)
  Changes:
  - Speed Curve Configuration Choices: Flat, Arctan, Cosin
  - E Axis (Rail) Option enabled
* CAD_files contains STL & STEP files

[Facebook Group](https://www.facebook.com/groups/robotarm)<br/>
[Discord Group](https://discord.gg/W5GUR7eSru)<br/>


Graphical contents and CAD files are licensed under CC BY 4.0 License. Community Firmware is licensed under GNU-3.0 License.

