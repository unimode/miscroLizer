miscroLizer
===========

Logic-analyzer/oscilloscope 2 analog and 4 digital channels.

Description:
 - platform: Stellaris LaunchPad EK-LM4F120XL REV A;
 - tools:    CCS v5, FreeRTOS, QTDesigner (Win/Lin), libusb;
 - UI:       two buttons and RGB LED (onboard), 2-lines symbolic LCD, host UI.

Interface

          Table 1. LaunchPad reserved pins
  _______________________________________________________________
 |  # |           |                |                |            |
 |    | GPIO PIN  |  PIN FUNCTION  |   DESCRIPTION  |   PINOUT   |
 |    |           |                |                |            |
 |----+-----------+----------------+----------------+------------|
 |  1 | PD4       |  USB0DM        |  D-            |            |
 |  2 | PD5       |  USB0DP        |  D+            |            |
 |  3 | PF0       |  GPIO          |  SW2           |            |
 |  4 | PF1       |  GPIO          |  LED RED       |            |
 |  5 | PF2       |  GPIO          |  LED BLUE      |            |
 |  6 | PF3       |  GPIO          |  LED GREEN     |            |
 |  7 | PF4       |  GPIO          |  SW1           |            |
 |  8 | PC0       |  ICDI          |  TCK/SWCLK     |            | *
 |  9 | PC1       |  ICDI          |  TMS/SWDIO     |            | *
 | 10 | PC2       |  ICDI          |  TDI           |            | *
 | 11 | PC3       |  ICDI          |  TDO/SWO       |            | *
 | 12 | PA0       |  U0RX          |  VIRTUAL COM   |            |
 | 13 | PA1       |  U0TX          |  VIRTUAL COM   |            |
 | 14 | RST       |  ---           |  ---           |            |
 | 15 | 3.3V      |  ---           |  ---           |            |
 | 16 | GND       |  ---           |  ---           |            |
 |_______________________________________________________________|



 * ICDI - Integration Circuit Debug Interface 



