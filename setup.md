* [Configurando Xbee Explorer USB Adapter](https://www.filipeflop.com/blog/como-configurar-xbee-explorer-usb/)

* [Comunicação Passo-a-Passo entre XBEE e Arduino](https://www.filipeflop.com/blog/tutorial-wireless-arduino-xbee-shield/)
  + Lembretes
    * remover Xbee Shield para carregar programa no arduino
    * resetar xbee (opção default) antes de cofigurá-lo 
* Hello world - OpenMV
  + [Download OpenMV IDE](https://openmv.io/pages/download)
  + File > Examples > OpenMV > Basics > helloworld.py
  + Tools > Save open script to OpenMV Cam (as main.py)
  + You have to click the connect button in the bottom left-hand corner of OpenMV IDE to connect to OpenMV Cam

* [Configurando Mosquitto (MQTT Broker) localmente no Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-the-mosquitto-mqtt-messaging-broker-on-ubuntu-16-04)
  + Substituir `sudo certbot certonly --standalone --standalone-supported-challenges http-01 -d mqtt.example.com` por `sudo certbot certonly --standalone --preferred-challenges http-01 -d mqtt.example.com`

