# nmaas87/docker-openwrt
OpenWRT Dockerfiles and Images for x86, x64, RPi, RPi2 and RPi3.

#### RPi, RPi2, RPi3 Images:
Docker Hub Repo: [https://hub.docker.com/r/nmaas87/rpi-openwrt/](https://hub.docker.com/r/nmaas87/rpi-openwrt/)
RPi, RPi2, RPi3 Images can only be used on ARM Hardware.
While RPi3 can work with RPi, RPi2, RPi3 Images, RPi2 work with RPi and RPi2 Images, the RPi Familiy (A/B/A+/B+/Zero/CM) can only work with RPi Images. It is encouraged to use the RPi Images with [Hypriot OS](https://blog.hypriot.com/), [balenaOS](https://www.balena.io/os/) or even [Raspbian](https://www.raspberrypi.org/downloads/raspbian/) with an manual Docker installation.

#### x86, x64 Images:
Docker Hub Repo: [https://hub.docker.com/r/nmaas87/docker-openwrt/](https://hub.docker.com/r/nmaas87/docker-openwrt/)
x86 and x64 need their plattform to work with.

===================================

#### Current Versions: 
These Versions were compiled on 15.02.2019 from the OpenWRT Repos and are updated on "as needed" base.

##### trunk (main development tree) [https://github.com/openwrt/openwrt/tree/master]
rpi / rpi2 / rpi3 / x86 / x64

##### 18.06 branch (current stable tree, Openwrt) [https://github.com/openwrt/openwrt/tree/openwrt-18.06]
rpi / rpi2 / rpi3 / x86 / x64

##### 17.01 branch (old stable tree, LEDE) [https://github.com/openwrt/openwrt/tree/lede-17.01]
rpi / rpi2 / rpi3 / x86 / x64

===================================

#### Legacy Versions: 
These Version were compiled on 08.05.2018 from the OpenWRT Repos and are legacy and are not updated anymore.

##### 15.05.1 branch (Chaos Calmer)
rpi / rpi2 / x86 / x64

These Versions were compiled on 13.12.2017 from the OpenWRT Repos before the re-merge with LEDE and are not updated anymore.

##### trunk_old (main development tree)
rpi / rpi2 / rpi3 / x86 / x64

These Versions were compiled on 22.01.2016 from the OpenWRT Repos, except 14.07_x86 and 15.05_x86 (forked from x-drum). These repos are not updated anymore.

#####  15.05 branch (Chaos Calmer)
rpi / rpi2 / x86 / x64

#####  14.07 branch (Barrier Breaker)
rpi / x86

#####  12.09 branch (Attitude Adjustment)
rpi / x86
