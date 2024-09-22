# zigbee Sniffer

## Overview
zigbee sniffer project using Nordic nrf802154 USB dongle.
## Key Features
Nordic documentaion:
- https://infocenter.nordicsemi.com/index.jsp?topic=%2Fsdk_tz_v4.1.0%2Fnrf802154_sniffer.html
- git submodule https://github.com/NordicSemiconductor/nRF-Sniffer-for-802.15.4

## installation and enviroment
Ubuntu 20.04
Jlink version 
minicom
wireshark

## Version
1.0

## steps
git clone this repo         \
### clone sub modules
` git submodule init`       \
` git submodule updadte`    



`cp nRF-Sniffer-for-802.15.4/nrf802154_sniffer/nrf802154_sniffer.py   /usr/lib/x86_64-linux-gnu/wireshark/extcap/
`

test communication with minicom 
## Author
khtb
20.9.2024
