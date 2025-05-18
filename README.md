# freewifi
The freewifi script is a straightforward Bash utility designed for wireless network analysis and deauthentication attacks. It enables users to capture packets from a specified wireless interface and execute deauthentication attacks on connected clients. This script is built with simplicity in mind, making it easy to extend and customize for various use cases. 

## Features
- Supports both 2.4GHz and 5GHz frequency bands.
- Option to set a random MAC address for the network interface.
- Ability to specify the number of deauthentication packets to be sent (default is 1).
- Option to utilize a wordlist for cracking WPA/WPA2 passwords.

## Prerequisites
- A compatible wireless network interface that supports monitor mode.
- Required tools: aircrack-ng, macchanger, and xterm.
- Root privileges are necessary to execute the script.

## Usage
```
usage: freewifi [options] <interface>
options:
  -5         : use 5GHz band
  -b         : set broadcast MAC address as destination
  -c <count> : number of deauthentication packets
  -m         : set random MAC
  -w <words> : path to wordlist filename
```
