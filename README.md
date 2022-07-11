# rpi_cam_web_interface_readme
Installation guide for optimum use of rpi_cam_web_interface 

Follow the installation instructions at https://elinux.org/RPi-Cam-Web-Interface

## Increase reliability
You may find that with the default RPi setup; filming, video conversion and other actions taking place at the same time causes recording to stop. This can be resolved with the following code at the bottom of /boot/config.txt 

### Be aware: this may void warranty
This is tested and works well on raspberry pi 3, other values may be more appropriate for other models;
```
force_turbo=1
over_voltage=2
```

## Always-on set-up
- Change "shedule settings"
- Change "DayMode" to "All Day"
- Change "Period Start" to "ca 1"
- Change "Motion Start" and "Motion Stop" to blank
