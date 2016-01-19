FROM scratch
MAINTAINER nmaas87 - https://github.com/nmaas87

ADD openwrt-brcm2708-rootfs.tar.gz /

RUN sed -i 's/12.09.1/12.09/g' /etc/opkg.conf

RUN mkdir /var/lock
USER root
CMD /sbin/init
