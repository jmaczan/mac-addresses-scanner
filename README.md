<p align="center"><img width="150" src="mac-addresses-scanner.png" alt="mac-addresses-scanner logo"></p>

# `mac-addresses-scanner`

Find MAC addresses of devices connected to given network.

## tl;dr

- Runs in terminal
- For Linux
- Pass network interface as first parameter, i.e. `wlp1s0`
- Pass IPs range as second parameter, i.e. `192.168.0.0/24`
- Needs to be ran with `sudo`
- Created in Python3 using [`Scapy`](https://scapy.net/)

## Run

`sudo ./mac-addresses-scanner wlp1s0 192.168.0.0/24`

## Build (from source code)

### Prerequisities
- Linux
- Python 3
- pip

### Run build
Run script `./build-from-source`

Output file will appear in folder `dist/`
