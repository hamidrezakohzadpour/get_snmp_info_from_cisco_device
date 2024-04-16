============================================================
Usage:
1. Install python 3 on windows.
2. Run cmd with elevated privilages and execute below commands:
	pip install napalm
	pip install colorama
	pip install netmiko
3. Make text file with name "device_ip.txt" and put on configs directory.
4. Add IP of cisco device to device_ip.txt file.
5. Put script to side of configs directory.
6. Add username and password of cisco device (privilage 15 required) into script.
	Switch = { 
            "hostname": ip_address,
            "username": "username",
            "password": "password",
            "optional_args": {"secret": "password"} 
            }
7. Run this command: python.exe script.py.
8. Script return a csv file contain of data of each cisco devices.
9. Import csv file into EXCEL and enjoy it.
============================================================
Tested on:
	windows 11,23H2 (OS Build 22631.3447)
	Python 3.12.0
============================================================
Hamidreza Kohzadpour, 2024, kohzadpour@gmail.com
============================================================