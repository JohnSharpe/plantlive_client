# plantlive_client
Behaviour for an Arduino-based collection of sensors to feed the plantlive application.

## Board
Board is the NodeMCU esp8266 wifi board.  
Add the following to "additional board managers URL" in arduino IDE preferences panel
```
http://arduino.esp8266.com/stable/package_esp8266com_index.json
```
This allows you to install the "esp8266" library (currently version 2.5.2) from "ESP8266 Community" using the Board Managers dialog.

Flash settings:
- Board: NodeMCU 1.0 (ESP-12E Module)
- Port: COM port with the arduino attached
- Others:default