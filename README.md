# datalabEindProject
Eindproject voor OLOD datalab S2 2025

# opbouw van het systeem

- raspberry pi 4 B
- ESP32 C3 supermini
- knop aan de rpi als sensor
- LED aan de rpi als actuator
- PIR aan de ESP
- de ESP stuurt data naar de pi via wifi
- de data wordt verwerkt via node-red
- node-red zet de data in influxdb
- grafana maakt een dashboard met de data in influxdb

# problemen met de RPi

omdat het meerdere keren (+10 keer imagen, +3 sd kaartjes geprobeerd) niet lukte om naar de pi via ssh te gaan, heb ik met docker op de VM gewerkt.

Daar werkt zowat alles met dank aan Jorik.


## Temp credentials

traefik:
student - admin
