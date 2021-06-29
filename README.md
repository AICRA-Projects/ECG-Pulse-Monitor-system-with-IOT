# ECG-Pulse-Monitor-system-with-IOT
Heart diseases are becoming a big issue for the last few decades and many people die because of certain health problems. Therefore, heart disease cannot be taken lightly. By analyzing or monitoring the ECG signal at the initial stage this disease can be prevented. So we present this project, i.e ECG Monitoring with AD8232 ECG Sensor & NodeMcu with ECG IOT Graph.

The AD8232 is a neat little chip used to measure the electrical activity of the heart. This electrical activity can be charted as an ECG or Electrocardiogram. Electrocardiography is used to help diagnose various heart conditions.

## What is ECG?
An ECG is a paper or digital recording of the electrical signals in the heart. It is also called an electrocardiogram or an EKG. The ECG is used to determine heart rate, heart rhythm, and other information regarding the heart’s condition. ECGs are used to help diagnose heart arrhythmias, heart attacks, pacemaker function, and heart failure.
# What is thingspeak?
ThingSpeak is IoT Cloud platform where you can send sensor data to the cloud. You can also analyze and visualize your data with MATLAB or other software, including making your own applications.
The ThingSpeak service is operated by MathWorks. In order to sign up for ThingSpeak, you must create a new MathWorks Account or log in to your existing MathWorks Account.
ThingSpeak is free for small non-commercial projects.
ThingSpeak includes a Web Service (REST API) that lets you collect and store sensor data in the cloud and develop Internet of Things applications. It works with Arduino, Raspberry Pi and MATLAB (premade libraries and APIs exists) But it should work with all kind of Programming Languages, since it uses a REST API and HTTP.
## ThingSpeak Communication Library for Arduino, ESP8266 and ESP32
This library enables an Arduino or other compatible hardware to write or read data to or from ThingSpeak, an open data platform for the Internet of Things with MATLAB analytics and visualization.
Hardware specific examples are found here. But to give you an idea of usage examples for writing and reading with an ESP8266 are shown below. Complete documentation in also shown below.

ThingSpeak offers free data storage and analysis of time-stamped numeric or alphanumeric data. Users can access ThingSpeak by visiting http://thingspeak.com and creating a ThingSpeak user account.

ThingSpeak stores data in channels. Channels support an unlimited number of timestamped observations (think of these as rows in a spreadsheet). Each channel has up to 8 fields (think of these as columns in a speadsheet). Check out this video for an overview.

Channels may be public, where anyone can see the data, or private, where only the owner and select users can read the data. Each channel has an associated Write API Key that is used to control who can write to a channel. In addition, private channels have one or more Read API Keys to control who can read from private channel. An API Key is not required to read from public channels. Each channel can have up to 8 fields. One field is created by default.

You can visualize and do online analytics of your data on ThingSpeak using the built in version of MATLAB, or use the desktop version of MATLAB to get deeper historical insight. Visit https://thingspeak.com/channels/647347 to learn more.
Libraries and examples for Arduino devices can be found here:https://github.com/mathworks/thingspeak-arduino
## Installation
In the Arduino IDE, choose Sketch/Include Library/Manage Libraries. Click the ThingSpeak Library from the list, and click the Install button.
--- or ---
Download the ZIP file (below) to your machine.
In the Arduino IDE, choose Sketch/Include Library/Add Zip Library
Navigate to the ZIP file, and click Open

## Methods
* AD8232 ECG Sensor should connect with Analog Pins of NodeMCU 
* Setup the probe with human body and connect with nodemuc with 5v power supply
* Red Light will get activate on AD8232 ECG Sensor
* SCAN  or visit the link in which thingspeak cloud graph has been displayed 
## Refernce
* https://thingspeak.com/
* https://www.analog.com/media/en/technical-documentation/data-sheets/ad8232.pdf
