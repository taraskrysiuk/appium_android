Docker container with appium and android sdk
======

#### Launch the image

Launch the image with *--privileged* option to allow docker instance to view connected USB devices:

``` bash
$ docker run -d -p 8888:4732 --privileged -v /dev/bus/usb:/dev/bus/usb --name appium rgonalo/appium
```
Appium server will be enable on -> 127.0.0.1:8888 - on host machine
