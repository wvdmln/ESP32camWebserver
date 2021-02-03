# ESP32camWebserver

Serial Monitor werkt via FTDI interface (opbouw breadboard)
Werkt ook met Chinese CH340 interface (ESP32cam op socket) op voorwaarde dat platformio.ini aangepast wordt
Voeg daarom volgende toe aan platformio.ini:  "monitor_dtr=0" en "monitor_rts=0"

Uncomment ook de juiste camera
