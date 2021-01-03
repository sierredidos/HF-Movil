# HF-Movil
Instalar java:
sudo apt-get update && sudo apt-get install oracle-java7-jdk

sudo tar -zxvf jAReC.jar -C /opt

mv jdk-8u91-linux-arm32-vfp-hflt.tar.gz /usr/local

cd /usr/local

tar -xzf jdk-8u91-linux-arm32-vfp-hflt.tar.gz

Dar permisos USB0:
sudo chmod 666 /dev/ttyS0
sudo chmod 666 /dev/ttyUSB0

Es necesario para que en la ventana Serial port y PTT serial port salgan ttyS0 Y ttyUSB0

Comando ejecución: java -jar jAReC.jar

Enlaces de interés:
https://www.yo3ggx.ro/

https://geekytheory.com/tutorial-raspberry-pi-11-como-instalar-java/
