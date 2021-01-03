# HF-Movil
Instalar java:<br>
sudo apt-get update && sudo apt-get install oracle-java7-jdk<br>
sudo tar -zxvf jAReC.jar -C /opt<br>
mv jdk-8u91-linux-arm32-vfp-hflt.tar.gz /usr/local<br>
cd /usr/local<br>
tar -xzf jdk-8u91-linux-arm32-vfp-hflt.tar.gz<br>
Es necesario para que en la ventana Serial port y PTT serial port salgan ttyS0 y ttyUSB0<br>
sudo chmod 666 /dev/ttyS0<br>
sudo chmod 666 /dev/ttyUSB0<br>

Comando ejecución: java -jar jAReC.jar<br>

Enlaces de interés:<br>
https://www.yo3ggx.ro/

https://geekytheory.com/tutorial-raspberry-pi-11-como-instalar-java/
