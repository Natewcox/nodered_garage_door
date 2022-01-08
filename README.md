# nodered_garage_door
Use Node-Red to make a HomeKit Garage Door Opener

## DESCRIPTION

I use HomeKit for my home automations and I am wanted to share how I use Node-Red to add each element. This repository is my Garage Door Opener. Not every user has Apple devices so I use this Raspberry as a dashboard to control the heater in my nodered_heater repo and a button to tell my Garage Door Raspberry to open.

## GETTING STARTED





### MATERIALS

1. Raspberry Pi
2. SD Card
3. 2 Magnetic Reed Switches
4. 5v 30a Relay
5. Wire

### WIRING


### INSTALLS

Fallow the directions at [RaspberryPi.org](https://www.raspberrypi.org) to:
  * Flash the latest Raspberry Pi imiage to the SDCard
  * Perform initial startup. Network and Update is a must.
***
Install Node-Red. The recommended software for the Raspberry includes Node-Red but is missing a few parts. Use the full install to have all files and updates.

```
bash <(curl -sL https://raw.githubusercontent.com/node-red/linux-installers/master/deb/update-nodejs-and-nodered)
```

Enable Node-Red at boot.

```
sudo systemctl enable nodered.service
```
If you plan to communicate between Pis, I recommend Mosquitto.
