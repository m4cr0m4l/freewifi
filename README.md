# freewifi
The freewifi script is a straightforward Bash utility designed for wireless network analysis and deauthentication attacks. By leveraging tools from the Aircrack-ng suite, it combines their functionalities to allow users to efficiently execute deauthentication attacks on connected clients and perform password cracking with a wordlist. 

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

## Donations
If you find this utility helpful and would like to support further development, consider making a donation in Bitcoin to the address `bc1qxp8va5r25s4pxc8yphs6dn7jfpq3n2r90hgn34`. You can also scan the QR code below to send your contribution. Your support will help fund the creation of more utilities and enhancements.

![address 00](https://github.com/user-attachments/assets/2c8af3d9-5390-4561-a208-5fa5c3d7ec18)

Thank you for your contribution!
