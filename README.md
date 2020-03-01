# Automatic Lock and Unlock System using Bluetooth

Python code for getting the RSSI value of a Bluetooth device by address. Based on the value returned, can determine the proximity of the device.

## Requirements

This code requires the `bluetooth` and `python-bluez` modules to be installed. On Ubuntu/Debian systems, this can usually be done with the following commands:

sudo apt-get install bluetooth
sudo apt-get install python-bluez

*Note: Your system must also have a Bluetooth adapter.

## Examples

### test_address.py

This is a simple script to scan and output the RSSI value of a Bluetooth address in a loop. This can be used to test if the code is working on your setup and also to output the detected RSSI values as you move your Bluetooth device closer/further from the Bluetooth adapter.

Use Ctrl + C to exit the script or wait until number of loops has finished.

python test_address.py <bluetooth-address> [number-of-loops]

## Notes

* The RSSI values returned will differ depending on your Bluetooth devices and your surroundings (e.g. are there walls/obstructions, multiple floors, etc).
* Use the test script mentioned above to see what values are returned in your setup.
* RSSI values may be positive or negative integers. You can use the absolute value (i.e. always positive) if you see both.




