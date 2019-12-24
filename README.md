Samsung Galaxy Note 4

Things that work without issue:


__ GUI

__ Touchscreen

__ Power Off Charging Animation

__ Status LED

Things that dont work:

__ QCOM Sensors

__ Bluetooth works GUI side but seems to refuse connecting at random and may crash device at random.

__ Cellular shows in GUI, not enough testing to verify if theres issues

__ Audio works, Media-hub appears to not be working (D-Bus errors)

__ Auto Brightness Sensor, have to toggle off then on to get working

Things that work with issue, and their issue

_X_ Bluetooth - Bluetooth initializes during boot (shows in dmesg) nothing GUI side

___ Wifi - Wifi network does not re-connect after a reboot

_X_ Cellular - Initializes in dmesg, no IMEI or anything GUI side

___ Stylus - Shows in DMESG and works in libinput, unity seems to ignore stylus

_X_ Audio - "aplay -l" shows devices, no way to interact or test actual audio

___ AppArmor - many profiles appear to be missing
