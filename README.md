# Current Home Assistant Configuration by [@cynicated](http://www.twitter.com/cynicated)

[Home Assistant](https://home-assistant.io) Configuration Files

I installed Home Assistant via the All In One installer.  It's running on a [Raspberry Pi 3 kit](http://amzn.to/2ez0qwI) I got from [Amazon](http://amzn.to/2f1UZaZ).

I started building out my home automation setup in 2016, and chose Z-Wave as it appeared to be the best and most widely supported.  To integrate it into Home Assistant, I'm using the [Aeon Labs Aeotec Z-Wave Z-Stick, Gen 5](http://amzn.to/2dDQ2E7).  So far, it's worked out the box with Home Assistant, and I am quite pleased with my setup.

**Current Devices**
- [GE Z-Wave Smart Toggle Switch (12727)](http://amzn.to/2f1Tolm)
- [GoControl Essential Z-Wave Home Security Suite (WNK01-21KIT)](http://amzn.to/2ehUPsS)
  - 1 Motion Sensor
  - 2 Door Sensors
- [First Alert 2-in-1 Z-Wave Smoke & Carbon Monoxide Alarm (ZCOMBO-G)](http://amzn.to/2eFb7M7)

**Current Functions**
- Tracking of residents via Owntracks & NMAP Scanning
- Manual Alarm System implemented using sensors
- LetsEncrypt configured
- Mosquitto MQTT  configured and functional
