# PFC_Mosquitto_Broker
Add a local mosquitto broker on PFC devices

# mosquitto-ipk
This repo contains an ipk file to add a loccal mosquitto broker on PFC 100/200 devices.


# How to install MQTT Broker on Wago devices.

## Prerequisites for tutorial
- Wago PFC or Wago Touch Panel with min. firmware 12 or higher installed in flash. 
- PC with preinstalled SSH Client (e.g. https://www.putty.org/)
- Web browser of your choice. (e.g. chrome).


## Installation

1. Start Wago PFC.
2. Open WBM (Web Base Management) menu "*Software Uploads*".
3. Press "*Browse*" button and navigate to wago mosquitto_x.x.x.ipk file. (e.g. mosquitto_1.4.14_armhf.ipk)
4. Then press "*Start Upload*" button.
5. After finishing the upload process, press "*Submit*" button to activate the software package. 
6. Just ignore possible error messages. 

## PFC Login
Start SSH Client e.g. Putty 
 ```bash
login as `root`
password `wago`
 ```
## Check docker-compose installation

```bash
mosquitto --version
 ```
## Known issues

## Links
 1. <a href="https://www.wago.com/de/" title="wago">https://www.wago.com/de/</a>
 
Enjoy the extented power of the whale!
