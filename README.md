# MQTT-ESP8266-IoT-DS18B20-Temperature
![MQTT](https://github.com/BehindTheSciences/MQTT-ESP8266-IoT-DS18B20-Temperature/blob/master/MQTT_Overview.png)
## INSTALL MOSQUITTO ON RASPBERRY PI RUNNING RASPBIAN STRETCH
```ruby
cd ~
wget http://repo.mosquitto.org/debian/mosquitto-repo.gpg.key
sudo apt-key add mosquitto-repo.gpg.key
cd /etc/apt/sources.list.d/
sudo wget http://repo.mosquitto.org/debian/mosquitto-stretch.list
sudo apt-get update
 
cd ~
wget http://security.debian.org/debian-security/pool/updates/main/o/openssl/libssl1.0.0_1.0.1t-1+deb8u7_armhf.deb
sudo dpkg -i libssl1.0.0_1.0.1t-1+deb8u7_armhf.deb
wget http://ftp.nz.debian.org/debian/pool/main/libw/libwebsockets/libwebsockets3_1.2.2-1_armhf.deb
sudo dpkg -i libwebsockets3_1.2.2-1_armhf.deb
```
