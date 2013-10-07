miscroLizer
===========

Logic-analyzer/oscilloscope 2 analog and 4 digital channels.

Description:
 - platform: Stellaris LaunchPad EK-LM4F120XL REV A;
 - tools:    CCS v5, FreeRTOS, QTDesigner (Win/Lin), libusb;
 - UI:       two buttons and RGB LED (onboard), 2-lines symbolic LCD, host UI.

Interface:
  __________________________________________________
 |  # |           |                |                |
 |    | GPIO PIN  |  PIN FUNCTION  |   DESCRIPTION  |
 |    |           |                |                |
 |----+-----------+----------------+----------------|
 |  1 | PD4       |  USB0DM        |  D-            |
 |  2 | PD5       |  USB0DP        |  D+            |
 |  3 | PF0       |  GPIO          |  SW2           |
 |  4 | PF0       |  GPIO          |  SW2           |
 |  5 | PF0       |  GPIO          |  SW2           |
 |  6 | PF0       |  GPIO          |  SW2           |
 |  7 | PF0       |  GPIO          |  SW2           |
 |  7 | PF0       |  GPIO          |  SW2           |
 |  7 | PF0       |  GPIO          |  SW2           |
 |  7 | PF0       |  GPIO          |  SW2           |
 |  7 | PF0       |  GPIO          |  SW2           |
 |  7 | PF0       |  GPIO          |  SW2           |






