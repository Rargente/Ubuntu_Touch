Samsung Galaxy Note 4

Things that work without issue:


__ GUI

__ Touchscreen

__ Power Off Charging Animation


Things that dont work:

__ QCOM Sensors


Things that work with issue, and their issue

__ Bluetooth - Bluetooth initializes during boot (shows in dmesg) nothing GUI side

__ Wifi - Wifi network does not re-connect after a reboot

__ Cellular - Initializes in dmesg, no IMEI or anything GUI side

__ Stylus - Shows in DMESG and works in libinput, unity seems to ignore stylus

__ Audio - "aplay -l" shows devices, no way to interact or test actual audio

__ AppArmor - many profiles appear to be missing
