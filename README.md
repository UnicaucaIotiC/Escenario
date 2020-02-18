# Escenario
Escenario de interaccion Semantica

Inicio Rapido

Configuración i2c

DEFINICIÓN DE I2C (I2C):
Abreviatura de Inter-IC (inter integrated circuits), un tipo de bus diseñado por Philips Semiconductors a principios de los 80s, que se utiliza para conectar circuitos integrados (ICs). El I2C es un bus con múltiples maestros, lo que significa que se pueden conectar varios chips al mismo bus y que todos ellos pueden actuar como maestro, sólo con iniciar la transferencia de datos. Este bus se utiliza en muchos dispositivos, en especial en equipos de vídeo como monitores de computadora, televisores y videocaseteras.

https://learn.adafruit.com/adafruits-raspberry-pi-lesson-4-gpio-setup/configuring-i2c 

sudo apt-get install python-smbus
apt-get install i2c-tools
Habilitar la configuración i2c: sudo raspi-config
Reiniciar y conectar la grovepi para probar la configuración. 
i2cdetect -y 1

Configuración GrovePi
http://www.dexterindustries.com/GrovePi/get-started-with-the-grovepi/setting-software 

cd /home/pi/Desktop
sudo git clone https://github.com/DexterInd/GrovePi
cd /home/pi/Desktop/GrovePi/Script
sudo chmod +x install.sh
sudo ./install.sh

Nueva Forma
https://github.com/initialstate/grovepi/wiki/Part-2.-GrovePi-Setup

$ sudo curl -kL dexterindustries.com/update_grovepi | bash
$ sudo pip install grovepi
$ sudo reboot



Configuración npm con NODEJS (Por ahora no lo usamos)

apt-get install npm
install nodejs npm
cd /home/pi/Desktop/GrovePi/Software/NodeJS
npm install latest
npm install registry
npm install brickpi-raspberry
npm search gpy
npm install node-gyp rebuild
npm install node-grovepi
Instalar npm install i2c-bus, npm install sleep, buffertools


Librerias 
https://pypi.python.org/pypi/suds comando sudo python setup.py install
https://pypi.python.org/pypi/paho-mqtt/1.1 comando sudo python setup.py install
easy_install web.py
