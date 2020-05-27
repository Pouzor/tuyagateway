TuyaMQTT
==================

Listens on MQTT topic and routes requests to Tuya devices, based on a one to one topic translation. 

Docs
================
https://github.com/TradeFace/tuyamqtt/wiki


Todo
===================
_v1.1.0_
- check config values

Changelog
==================
_v1.1.0_
- Ctrl+C does not stop server #3
- listen for kill signal from mqttdevices
- device config via topic is rather crude
  - https://github.com/TradeFace/mqttdevices has to solve this (WIP)
  - add tuyamqtt Autodiscovery #28
- Remove availability logic from TuyaMQTTEntity.status #26

_v1.0.0_
- clean up
- bump tuyaface to v1.2.0
- removed hass_discovery
- moved UI basics -> https://github.com/TradeFace/mqttdevices 
- bump tuyaface to v1.1.7 
  - near instant status updates on manual device handling
- bump tuyaface to v1.1.6
- implemented logger and removed custom debugger
- tuyaface to v1.1.5
- clean up dockerfile
- check requirements.txt 
- replaced entities.json with sqlite db
- only publish onchange
- added via mqtt/tuya
- thread per device
- pytuya replaced by https://github.com/TradeFace/tuya

Acknowledgements
=================
- https://github.com/SDNick484 testing protocol 3.1 reimplementation
- https://github.com/emontnemery development tuyaclient and implementation in tuyamqtt
- https://github.com/jkerdreux-imt testing tuyaclient

