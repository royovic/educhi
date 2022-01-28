# Materials and Code for the Data-Enabled Design workshops to be presented at eduCHI.

Submission "Hands-on Pedagogical Activities to Onboard Design Students in the Use of Sensor Data as a Creative Material"

Use the Instructions file to setup your software and hardware for the Workshop. It's recommended to have students install this before the workshop starts. 

# Reading Sensors

For Code Examples, we recommend the following examples as boilerplate code:

For quickly reading sensor values of Analog sensors (LDR, pressure sensor, etc.)
In Arduino IDE: /Examples/Basics/AnalogReadSerial

For reading a DHT11/22 Temperature Sensor
Install DHT Sensor Library by Adafruit via the Library Manager in Arduino IDE
In Arduino IDE: /Examples/DHT sensor library/DHT_Unified_Sensor 
Uncomment the correct DHT sensor and verify the breadboard wiring is correct.

# Using OOCSI 

When using OOCSI, make sure to use a unique OOCSIName. 
You can use the public OOCSI server with "oocsi.id.tue.nl" , 
Set the channelname with this line: oocsi.newMessage("CHANNELNAME");

For sending data to OOCSI
In Arduino IDE: /Examples/OOCSI/OOCSI_Sender

For receiving data from OOCSI
In Arduino IDE: /Examples/OOCSI/OOCSI_Receiver

For sending data to a Data Foundry IOT Dataset:
In Arduino IDE: /Examples/OOCSI/DataFoundry/IoT_dataset

Learn more about OOCSI here: https://github.com/iddi/oocsi
