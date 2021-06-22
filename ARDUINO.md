#  ARDUINO CAN'T CONNECT TO PORT dev/ttyUSB0

1. `sudo groupadd dialout`
2. `sudo gpasswd -a USER dialout`
3. `sudo usermod -a -G dialout USER`
4. `sudo chmod a+rw /dev/ttyUSB0`
