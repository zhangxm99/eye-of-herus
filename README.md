# eye-of-herus

![svg](./Eye_of_Horus_bw.svg)

## Introduction

It's a complet BVR-UAV control system. In this project, the Raspberry Pi is used as the drone control terminal, and the port of the Raspberry Pi is mapped on the public network through NAT technology. The computer accesses the web page to obtain real-time images and control the operation of the aircraft.

## Usage

1.install dependencies
```
pip3 install picamera ws4py
```
2.run server on raspberrypi
```
python3 server.py
```
3.input your NAT server address in web browser and control

## Based on

* https://github.com/Onixaz/picamera-h264-web-streaming/
