# Instructions for preparing the software 

These instructions are used for the Wemos D1 mini (v3), Arduino IDE and OOCSI.

# Install Arduino

Install Arduino IDE: https://www.arduino.cc/en/Main/Software

# Install ESP8266 library

Start Arduino and open Preferences window.
Enter https://arduino.esp8266.com/stable/package_esp8266com_index.json into Additional Board Manager URLs field. 
You can add multiple URLs, separating them with commas.
Open Boards Manager from Tools > Board menu and find esp8266 platform.
Select the latest version from the drop-down box. (NOTE: we had some wifi issues with espressifs 3.0.0 version and OOCSI, 2.7.4 version of the esp8266 library works definitely)
Click install button.

# Install Wemos D1 USB driver

Download the USB driver from: https://www.wemos.cc/en/latest/ch340_driver.html 
Install the driver (launch setup and check out ‘help’)

Don’t forget to select your Wemos D1 mini board from Tools > Board menu when uploading code.

# Install OOCSI library

Download the latest version from: https://github.com/iddi/oocsi-esp/releases
Open the Arduino IDE and go to Sketch > Include a library > Add .ZIP library
Select the downloaded ZIP file containing the OOCSI ESP release.
Restart Arduino IDE.
Go to the Arduino IDE and check whether File > Example > OOCSI is visible.

# Install ArduinoJSON library (required for OOCSI)
Open the Arduino IDE and go to Sketch > Include a library > Manager Libraries
Search for ‘ArduinoJson’and look for the entry by Benoit Blanchon
Select the latest version in the dropdown box and press Install
Go to the Arduino IDE and check whether File > Example > ArduinoJson is visible

# Troubleshooting

Students often run into trouble with installing libraries and uploading code. Check for the following:

1. Use a proper USB cable (so, with datapins, not just power)
2. Make sure the Wemos D1 is not short-circuited when hooked up to a breadboard with components
3. Check that the libraries are installed in the right folder (e.g. USER/Documents/Arduino/libraries)
4. Check that the right COM port is selected (if the CH340 driver isn't installed properly, it won't detect the Wemos)
5. If it isn't connecting to Wifi, check whether the device (MAC) is allowed on the network in case of school-network
6. If it is stuck connecting to Wifi, check whether the esp8266 library (3.0.0) isn't interfering with other libraries. If not sure, downgrade to earlier version.

# Data Foundry
If you want to use Data Foundry as a data-storage platform, these are the instructions for setting it up:

Go to https://data.id.tue.nl/
Make an account and fill in the required info.
Make a new project and fill in the required info.
Add an IOT Dataset
Go to the IOT Dataset and enter the OOCSI Channel name in OOCSI Stream
Go the Manage Resources
Add a Device and fill in the info. Use the Device ID in your sketch if required (depends on OOCSI library version).
Check out the data coming in by opening the IOT dataset

Optional: Use the Data Foundry Data Visualisation option (here: https://data.id.tue.nl/tools/rawgraphs)






