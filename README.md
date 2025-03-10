# OpenEVSE_PLUS
README.md for OpenEVSE Hardware
Files SCH and BRD in Eagle format
License CC BY-SA 3.0
OpenEVSE Hardware


Current Version OpenEVSE_PLUS_v6.5.1.

<img src="https://github.com/OpenEVSE/OpenEVSE_PLUS/blob/master/OpenEVSE_PLUS_v6.5.1/OpenEVSE_PLUS_V6.5.1.png" alt="OpenEVSE Electric Vehicle controller v5.5 SAE J1772 IEC 61851">

OpenEVSE_PLUS_V6.5 - New more powerfull 10 watt Power supply (v5.5 and below 4 watt) with support for 277V AC and higher 85C operational temperature. Reworked AC detect circuits to support new UL requirement for "Continuous" Ground Monitoring vs "While Charging". Added on-board Surge supression MOVs. Added connector with Pilot, Proximity Pilot, Ground and 5v.

<img src="https://github.com/OpenEVSE/OpenEVSE_PLUS/blob/master/OpenEVSE_PLUS_v5.5/OpenEVSE_v5.5.jpg" alt="OpenEVSE Electric Vehicle controller v5.5 SAE J1772 IEC 61851">

OpenEVSE_PLUS_V5.5 - Moved GFCI Test pin to enable move of DC Relay outputs to PWM capable pins supporting full power closing reduced power holding in OpenEVSE 7.1.2+ firmware. Added GPIO pin pulled HIGH to auto detect board version in software to automatically set new/old pin values without requiring different firmware. Replaced 0.1" generic non-polarized connectors with JST PH for Serial (WiFi) and i2c (Display). Combined power and data connections for WiFi to reduce eliminate a screw terminal connector and simplify wiring harness. Replaced DC/DC converter with a TC1044S invert chip to generate -12v from +12v. 
 

<img src="https://github.com/OpenEVSE/OpenEVSE_PLUS/blob/master/OpenEVSE_PLUS_v5/OpenEVSE_v5.jpg" alt="OpenEVSE Electric Vehicle controller v5 SAE J1772 IEC 61851">

OpenEVSE_PLUS_v5 - Optimized for reduced build time and high volume manufacturing of changing stations, removed most screw terminals and replaced with common connectors. Change from 2 single chanel opto-isolators for AC detection to 1 dual channel. Added ground connections to screw holes.

<img src="https://github.com/OpenEVSE/OpenEVSE_PLUS/blob/master/OpenEVSE_PLUS_v4/OpenEVSE_v4.jpg" alt="OpenEVSE Electric Vehicle controller v4 SAE J1772 IEC 61851">

OpenEVSE_PLUS_v4 - Has 2 AC Detect chips like v1 + v2 plus the AC relay driver of v3. Added rectifier diodes to AC detect to improve detection in some conditions. Changed GFCI to individual pinout 4 pins.

OpenEVSE_PLUS_v3 - Removed 1 AC Detect chip and added AC relay driver. Added Current measurement circuit

OpenEVSE_PLUS_v2.5 - Added Current measurement circuit.

OpenEVSE_PLUS_v2 - modified GFCI pinout

OpenEVSE_PLUS_v1 - Inital version - Combined OpenEVSE v7 board and Advanced power supply into single board 
