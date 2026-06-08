# Changelogs

## 2.1.6
 - The change from the last release is the integrated automatic masking or suppression/delay of certain errors and the resulting automatic reset of the lights. (Applies only to procontrol v2)

## 2.1.4-1	
 - Liol-E Clock output allows Logic when tower light clock = off
 - Various fixes for FTP upload of log files

## 2.1.4	
 - Generation of Liol-E clock with external GPS

## 2.1.3	
 - Compatibility for new aviation light firmware

## 2.1.2-2	
 - GPS messages are output with a delay

## 2.1.2-1	
 - Support for older logic formats

## 2.1.2	
 - License system for new features integrated
 - Modbus/TCP and Modbus/RTU implemented (ALI mode and digital inputs and outputs)

## 2.1.1	
 - New Aviation Light types
 - Input of WT number and display in park overview

## 2.1.0	
 - Adaptation of the code and the optics for both proControls
 - Reset the visibility meter after cleaning
 - Delay of tower light fault (no time relay)
 - Renewal of the help file

## 2.0.0-4 (nur v2)
 - Bugfixes
  
## 2.0.0-3 (nur v2)
 - Revision of the logic controller firmware and thus correction of minor errors
 - Improved detection of defective or incorrect configuration files
 - Minor corrections of spelling errors in the web interface (including translation)
 - Updating the clock code designations
 - Detection and display of RS485 communication problems with the fires
 - Detect and display communication problems with the logic controller

## 1.0.4-12 (nur v1)
 - Bugfixes
  
## 1.0.4-10 (nur v1)
 - Adaptation of the representation in the status of the lights
 - Limitation of the system log file to 2 MB
 - Check and, if necessary, repair the SD card at startup

## 1.0.4-8 (nur v1)
 - Monitoring the light sensor warnings of the aviation lights
 - Optimization RS485 Communication with the aviation lights

## 1.0.4-2 (nur v1)
 - Tower light error remains during the day
 - Correction of the display of the GPS offset under "Control & Config" for proFeuer types
 - View Flash Frequency 09 as "DAY: ICAO 20fpm, NIGHT: off"
 - Button "Reset Warnings and errors" now under "Control & Config" and usable for all logged-in users

## 1.0.4-1 (nur v1)
 - Input DI14 Overvoltage protection OK now is shown as warning

## 1.0.4 (nur v1)
 - Support for day/night lights pro20A/B/W
 - You can now connect different proFeuer variants. The respective type is read out via RS485. Depending on the type, a corresponding "configuration data model" is selected internally, which primarily defines the different number and assignment of LED controllers. According to the model in the web interface under "System Settings", the appropriate LED controller settings are displayed and can be changed there
 - In addition, the status next to Aviation Light 1 and Aviation Light 2 displays the respective detected light type
 - For the new aviation light types corresponding predefined devices were added in the serial number input
 - Improving the speed of the web interface, the individual pages are now loaded and displayed faster
 - Automatic Reset of connected proFeuer when restarting proControl
 - Switching from GET to POST requests to avoid caching issues when using Internet Explorer
 - Improving the reliability of the update process, incompletely unzipped update files (such as premature reboot) can no longer cause invalid data to be written to Flash by mistake
 - Corrections and improvements to the display of MOR status, although the reported error could not be fully reproduced, corrections and improvements were made in the display of MOR status
 - Safer writing of configuration files to SD card
