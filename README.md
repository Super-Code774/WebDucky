This is a version of the rubber ducky by Hak5 for the Raspberry Pi Pico W.

This version spawns an access point and a webserver from which the Pico can be controlled, and Keystrokes can be sent.

# Requirements
For this setup, Adafruits Circuitpython on a Raspberry Pi Pico W is needed.
Also make sure to download the HID libs from adafruit from https://github.com/adafruit/Adafruit_CircuitPython_HID

# Setup
After installing the files on the Pico, plug it in and connect to the access point specified in the secrets.py file, modify the data for your needs.

Set up the keyboard layout in hid.py by editing the lines as written in the comments
