# homeassistant-config


In custom_components there are two libraries linked. 

- Localtuya https://github.com/TradeFace/localtuya-homeassistant (fork with minor tweak) 
- HassVariables https://github.com/rogro82/hass-variables

System Parts
-----------
- Raspberry Pi 3
- xiaomi ir remote
_beamer and surround control_
- xiaomi gateway (lumi.gateway.v3)
_motion and temperature sensors_
- BHT6000-X Themostat
_base heating control_ 
https://github.com/klausahrenberg/ThermostatBecaWifi
- sonoff 4CH Pro (flashed with Tasmota)
_infrared heating zone switching_
- Wemos D1 mini (flashed with Tasmota)
_infrared heating zone temperature sensors_
- Vgate iCar3 (comming up)
_presence detection_
- Landis + Gyr 
_smart meter_ 
https://github.com/TradeFace/smmqtt
- Wifi-RTU 
_solar gateway_
https://github.com/TradeFace/shinemonitor

Todo
-------------
- hallway lighting switch not found
- solar feed not working
- movie scene needs testing
- hallway first switch set landing light automation
- add pir kitchen + corridor
- add button bedroom 1
- purge data
- pull data to external drive (influx)

Todo Datascience
--------------
-  
