# homeassistant-config


In custom_components there are two libraries linked. 

- Localtuya https://github.com/TradeFace/localtuya-homeassistant (fork with minor tweak) 
- HassVariables https://github.com/rogro82/hass-variables

Objective
-----------
- home-assistant db is stored in ramdisk
- on reboot the db is lost
- important data should be stored on an external device
- data analysis / function modeling can on external device
- HA should put latest model on boot and periodically 

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
- sonoff mini (flashed with Tasmota)
_bathroom main light, triggered with tuya wifi switch_
- sonoff basic (flashed with Tasmota)
_kitchen lights_
- sonoff wifi socket s26 (flashed with Tasmota)
_infrared heating zone switching_
- Wemos D1 mini (flashed with Tasmota)
_infrared heating zone temperature sensors_
- Landis + Gyr 
_smart meter_ 
https://github.com/TradeFace/smmqtt
- Wifi-RTU 
_solar gateway_
https://github.com/TradeFace/shinemonitor

Todo
-------------
- hallway lighting switch not found -> pytuya can't handle the switch somehow
- movie scene needs testing -> surround on delay
- hallway first switch set landing light automation
- purge data - purge is set in conf, but doesn't seem to work correctly
- pull data to external drive (influx)
- bathroom main light lags
- switch ventilation system on/off
- iCar3 goes in to sleep mode after 30m, need to unplug/replug to get it back online
-- need other solution for car presence detection
- temp sensor on woodstove  
- add automations for cube
- presence automation not working correctly

Todo Datascience
--------------
- setup influx
- setup graphana
- setup jupyter
- learn heating
- learn scenes 
