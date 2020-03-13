# inverter_232_mppsolar_raspberry
Modem Red project to comunicate with the chiese inverter and storie data in the include database


//LINKS TO WEBSITE USED TO LEARN NODERED AND 232 COMUNICATION
https://pimylifeup.com/raspberry-pi-grafana/
https://pimylifeup.com/raspberry-pi-influxdb/
http://www.pierolucarelli.it/codiciascii/Tabella%20ASCII%20strandard.htm
https://www.lammertbies.nl/comm/info/crc-calculation
https://www.youtube.com/watch?v=M0Mjo0J1X_Q


//HARDWARE
-solar inverter like MPPSOLAR (different brand but same type)
-raspberry pi3
-rs232 to ttl converter
-ethernet cable
-rj45 plug


//HOW IT WORKS
the inverter is connected to the raspberry trought the serial port. raspberry serial port is TTL. inverter serial port is RS232. the converter is needed to adapt the RS232 signal to TTL.
into raspberry node red is enabled and set for start at the boot. also influxdb and grafana are installed and set for boot start.

for now i only share the image of the user interface that i made. later with time i will insert all the information to do this project and the final code.
the user interface is visible on the smarphone and on the PC. for now it is only il local network. in the future i will upgrade the project to be accessible trought internet.
