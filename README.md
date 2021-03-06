# aci_monitor
> A simple python library to query interface status from Cisco APIC.

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
The purpose of this project is to generate a REST call to Cisco APIC and show interface throughput statistics.

## Screenshots
![Example screenshot](./img/aci_monitor_screenshot.png)

## Setup
* This project was tested on python 3.7.6.
* Clone the project
* Create virtual environment: `python -m venv env`
* Activate the virtual environment: `source env/bin/activate`
* Add library requirement: `pip install -r requirements.txt`
* Change the APIC's IP and credentials in settings.json
* Modify the intf_list.json and add the interfaces to monitor
* Run program: `pyhon main.py`

## Code Examples
Show examples of usage:
python main.py

## Features
List of features ready and TODOs for future development
* Monitor interface's ingress/egress Bps and Pps

To-do list:
* Add other type of queries

## Status
Project is: _in progress_

## Inspiration
Project inspired by many customer requests for a simple way to monitor switch interfaces.
Thanks README.md template from https://github.com/ritaly/README-cheatsheet

## Contact
Created by [@disruptednetwork(https://github.com/disruptednetwork) - feel free to contact me!
