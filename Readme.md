# MAChanger
A Simple Python script to change your MAC address to random value or specify a new one.

## Installation
git clone https://github.com/sairam-298/MAC-address-spoofing.git
cd MAChanger


## Usage
Usage: MAChanger.py [options]

Options:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface INTERFACE
                        Interface to change its MAC address
  -m NEW_MAC, --mac=NEW_MAC
                        New MAC address
  -r RANDOM,  --random RANDOM (Default)
                        Generate a random MAC Address
      

## Example
sudo python2 MAC-addressing-spoofing.py --interface eth0 --mac 00:34:12:78:9a:bc
