# raspicenter
raspicenter docker installation incl. configurations
all parts of this system are docker containers

### Homeautomation using Apple Homekit as Human Interface
- central mqtt server
- homebridge with mqttthing plugin and javascript codecs as 'glue' between systems
- Shelly Switches on a separated subnet behind standard wall switches, connected to the central mqtt server
- zigbee2mqtt with conbee II zigbee stick for IKEA Tradfri Lightbulbs and Philips HUE Switches
- ESP32Somfy-RTS on an ESP32S-Wroom board with CC1101 Tranceiver Module to operate motored window shades

no cloud connection
no regular updates braking the home autionation every 2 month (Apple Homekit with tradfri and HUE routers)

### Installation.
RaspberryPi 4
dockerengine
git pull the repository

### Operation
```
  . _start
```
download & start all docker containers

```
  . _stop
```
stop all containers & networks.

