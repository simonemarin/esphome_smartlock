# esphome_smartlock
Starter project to build a smart lock device using ESPhome https://esphome.io/, a NEMA17, a stepper driver, a figerprint sensor (optional), a couple of switches, a passive buzzer and some 3d printed parts.

## Disclaimer
This is an ad-hoc project which worked for my door but may not for yours, still it may be a starting point for your project, feel free to join and feed back.

Components used:
- NodeMCU v2 (esp8266) https://aliexpress.ru/item/32665100123.html
- NEMA17 (dual shaft is a plus if you want to unlock yourself when the power is off) https://www.aliexpress.com/item/32906078178.html
- stepper driver a4988 https://www.aliexpress.com/item/1005001374747956.html
- 12v power supply https://www.aliexpress.com/item/1005002193618385.html
- a door lock cylinder with handle, the one I used has a D shaped 8mm shaft https://www.leroymerlin.es/fp/82337473/cilindro-niquelado-llave-puntos-boton-standers
- 8mm to 5mm shaft coupler https://es.aliexpress.com/item/4000259884542.html 
- GROW fingerprint sensor 502aw but any of the series should work http://www.zjgrow.com/GROW-Capacitive-Fingerprint-Scanner-Sensor-Module-Reader-Access-Control-c39195/
- a small switch (this is the only invasive part, you have to place the switch inside the lock system, it may opt out and do some software magic)
- a switch for the frontend (also optional)
- access to a 3D printer (I am including the blender project, you will have to adapt it to your door)

To add fingerprint functionality you have to pull a specific branch of ESPhome, thay may change soon, please follow up here https://github.com/esphome/esphome/pull/1356

To store fingerprints and do something with it add https://github.com/simonemarin/esphome_smartlock/blob/main/ha_fingerprint_package.yaml to Home Assistant 
