# Useful commands for Home Assistant

A list of useful commands when working with Home Assistant from the command line.  These commands are taken from my experience on the Raspberry Pi 3, running the home assistant all in one installer and may not work for other install types.

## Home Assistant

**Restart Home Assistant**

Necessary after updating configuration files:  
`sudo systemctl restart home-assistant`

## Mosquitto

**Restart the Mosquitto Service**

`sudo systemctl restart home-assistant`

**Add users to Mosquitto**

To create the mosquitto passwd file:  
 `sudo mosquitto_passwd -c /etc/mosquitto/pwfile <username>`

 Once it is created, you can add users by:  
 `sudo mosquitto_passwd /etc/mosquitto/pwfile <username>`

**Subscribe to Mosquitto Topic**

To subscribe to all messages coming to the server:  
 `mosquitto_sub -h <server> -p 1883  -t "#" -u <username> -P <pass> -v`
