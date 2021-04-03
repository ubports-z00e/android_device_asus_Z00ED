Device Checklist
================

Working
-------
* Actors: Manual brightness
* Actors: Notification LED
* Actors: Vibration
* Camera: Flashlight
* Camera: Photo
* Camera: Switch between back and front camera
* Camera: Video
* Cellular: Carrier info, signal strength
* Cellular: Data connection
* Cellular: Enable/disable mobile data and flightmode works
* Cellular: Incoming, outgoing calls
* Cellular: MMS in, out
* Cellular: PIN unlock
* Cellular: SMS in, out
* Cellular: Switch connection speed between 2G/3G/4G works for all SIMs
* Endurance: Battery lifetime > 24h from 100%
* GPU: Boot into UI
* Misc: AppArmor patches applied to kernel
* Misc: Battery percentage
* Misc: Offline charging (Power down, connect USB cable, device should not boot to UT)
* Misc: Online charging (Green charging symbol, percentage increase in stats etc)
* Misc: SD card detection and access
* Misc: Shutdown / Reboot
* Sensors: Proximity
* Sensors: Rotation
* Sensors: Touchscreen
* Sound: Earphones buttons volume control
* Sound: Earphones detected
* Sound: Earphones microphone
* Sound: Loudspeaker
* Sound: Loudspeaker volume control
* Sound: Microphone
* WiFi: Enable/disable and flightmode works
* WiFi: Hotspot can be configured, switched on and off, can serve data to clients

Working with additional steps
-----------------------------
* WiFi: Driver loaded at startup - does not work on first boot

Not working
-----------
* Actors: Torchlight
* Bluetooth: Driver loaded at startup
* Bluetooth: Enable/disable and flightmode works
* Bluetooth: Pairing with headset works, volume control ok
* Bluetooth: Persistent MAC address between reboots
* Cellular: Change audio routings
* Cellular: Switch preferred SIM for calling and SMS
* Cellular: Voice in calls
* Misc: Anbox patches applied to kernel
* Misc: Date and time are correct after reboot (go to flight mode before)
* Misc: Offline charging battery percentage
* Misc: Recovery image builds and works
* Misc: Reset to factory defaults
* Sensors: GPS
* USB: ADB access
* USB: MTP access
* WiFi: Persistent MAC address between reboots

Untested
--------
* Endurance: No reboot needed for 1 week
* GPU: Hardware video decoding
* Sensors: Automatic brightness
* Sound: Earphones buttons

Porting notes
=============
TODO
-----
* Fix rsyslogd hanging (https://github.com/ubports/ubuntu-touch/issues/560#issuecomment-590060779)
* Fix offline charging battery percentage
* Fix low performance?
* Fix voice and microphone in calls
* Fix dual SIM issues
* Fix torchlight in `indicator-power`
* Fix time sync issues after reboot with flight mode enabled
* Fix bluetooth
* Fix GPS
* Apply Anbox kernel patches
* Enable MTP & ABD
* Build UBports recovery image
* Create config for [devices.ubuntu-touch.io](https://www.google.com "Ubuntu Touch supported devices")
* Fix reset to factory defaults
* UBports installer support
* OTA updates and official support?
* Fix WiFi MAC address
* Enable Hall sensor
* Cleanup
* Add support for installing to /system for 8GB devices
