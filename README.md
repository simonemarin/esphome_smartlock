# esphome_smartlock
Starter project to build a smart lock device using ESPhome https://esphome.io/, a NEMA17, a stepper driver, a figerprint sensor (optional), a couple of switches, a passive buzzer and some 3d printed parts.

## Disclaimer
This is an ad-hoc project which worked for my door but may not for yours, still it may be a starting point for your project, feel free to join and feed back.

Components used:
- NodeMCU v2 (esp8266)
- NEMA17 (dual shaft is a plus if you want to unlock yourself when the power is off)
- stepper driver a4988
- 12v power supply
- GROW fingerprint sensor 502aw but any of the series should work http://www.zjgrow.com/GROW-Capacitive-Fingerprint-Scanner-Sensor-Module-Reader-Access-Control-c39195/
- a small switch (this is the only invasive part, you have to place the switch inside the lock system, it may opt out and do some software magic)
- a switch for the frontend (also optional)
- access to a 3D printer (I add the blender project you will have to adapt it to your door)


