Device Checklist
================

Working
-------
* Actors: Manual brightness
* Actors: Notification LED
* Actors: Vibration
* Camera: Flashlight
* Camera: Photo
* Camera: Video
* Camera: Switch between back and front camera
* Cellular: Carrier info, signal strength
* Cellular: Data connection
* Cellular: PIN unlock
* Cellular: SMS in, out
* Cellular: Incoming, outgoing calls
* Cellular: Switch connection speed between 2G/3G/4G works for all SIMs
* Cellular: Enable/disable mobile data and flightmode works
* Cellular: Switch preferred SIM for calling and SMS
* GPU: Boot into UI
* Misc: AppArmor patches applied to kernel
* Misc: Battery percentage
* Misc: Offline charging (Power down, connect USB cable, device should not boot to UT)
* Misc: Online charging (Green charging symbol, percentage increase in stats etc)
* Misc: SD card detection and access
* Misc: Shutdown / Reboot
* WiFi: Driver loaded at startup
* WiFi: Enable/disable and flightmode works
* WiFi: Persistent MAC address between reboots
* WiFi: Hotspot can be configured, switched on and off, can serve data to clients
* Sensors: Rotation
* Sensors: Touchscreen
* Sound: Loudspeaker
* Sound: Microphone
* Sound: Loudspeaker volume control

Working with additional steps
-----------------------------
*nothing here*

Not working
-----------
* Actors: Torchlight
* Bluetooth: Driver loaded at startup
* Bluetooth: Enable/disable and flightmode works
* Bluetooth: Persistent MAC address between reboots
* Bluetooth: Pairing with headset works, volume control ok
* Cellular: Voice in calls
* Cellular: Change audio routings
* Misc: Anbox patches applied to kernel
* Misc: Recovery image builds and works
* Misc: Reset to factory defaults
* Misc: Date and time are correct after reboot (go to flight mode before)
* Sensors: GPS
* USB: MTP access
* USB: ADB access

Untested
-----------
* Cellular: MMS in, out
* Endurance: Battery lifetime > 24h from 100%
* Endurance: No reboot needed for 1 week
* GPU: Hardware video decoding
* Sensors: Automatic brightness
* Sensors: Proximity
* Sound: Earphones detected, volume control
