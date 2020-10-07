# ActAll
Basic Script for does a full update in a RaspBerryPi 4.

The script:
- apt-get update
- apt-get upgrade
- rpi-update

if you use the argument '-y' the script does a reboot of the system automatically,
however if you don't put any arguments, the script ask you if you want to reboot the system.
