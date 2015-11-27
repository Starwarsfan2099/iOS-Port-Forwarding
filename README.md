#SSLStrip Possible on iOS!
This package allows you to port forward all traffic through a proxy on your iOS device. This is the same as using iptables on Linux systems to port forward.

#Requirements

+Python2.7

+Sslstrip

+Twisted Modules

+This package

+Arpspoof(Dsniff Suite)

All of these can be downloaded from my repo: http://www.starwarsfan2099.x10host.com/repo

# Install

Copy all of the contents to /etc on the iOS device.

#Usage

After a successful start of sslstrip and arpspoofing, run this command: pfctl -e -f pf_ssl.conf

To stop: Reboot Device :)

# Problems
If you receive a no module named twisted error: Copy /usr/lib/python2.5/twisted to /usr/lib/pyhton2.7
