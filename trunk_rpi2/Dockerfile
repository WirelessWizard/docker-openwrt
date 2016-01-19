FROM scratch
MAINTAINER nmaas87 - https://github.com/nmaas87

ADD openwrt-brcm2708-bcm2709-raspberrypi-2-rootfs.tar.gz /

RUN sed -i 's/\/trunk\/brcm2708\/bcm2708\//\/trunk\/brcm2708\/generic\//g' /etc/opkg/distfeeds.conf

RUN mkdir /var/lock
USER root
CMD /sbin/init
