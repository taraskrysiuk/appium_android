Docker container with appium and android sdk
======

#### Launch the image

Launch the image with *--privileged* option to allow docker instance to view connected USB devices:

``` bash
$ docker run -d -p 8888:4723 --privileged -v /dev/bus/usb:/dev/bus/usb --name appium taraskrysiuk/appium_android
```
Appium server will be enable on -> 127.0.0.1:8888 - on host machine

Installed soft:
  jdk 8;
  android sdk 24.4
  appium 1.5.3
