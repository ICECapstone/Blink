# Lecture1_Blink
My first NodeMCU code - Blink ;-)

On your Arduino IDE, 
Go to File -> ESP8266 -> Blink

Remember to set up your NodeMCU
1. Install WiFi library
Go to Sketch -> Include library -> Manage libraries
Select WiFi Built-in by Arduino 

2. Set up your Arduino IDE 
Go to File->Preferences and copy the URL below to get the ESP board manager extensions: http://arduino.esp8266.com/stable/package_esp8266com_index.json Placing the http:// before the URL lets the Arduino IDE use it...otherwise it gives you a protocol error.

3. Go to Tools > Board > Board Manager> Type "esp8266" and download the Community esp8266 and install. 

4. Set up your chip as:
Tools -> Board -> NodeMCU 1.0 (ESP-12E Module)
Tools -> Flash Size -> 4M (3M SPIFFS)
Tools -> CPU Frequency -> 80 Mhz
Tools -> Upload Speed -> 921600
Tools-->Port--> (whatever it is)
