a fortinet plugin for logwatch
==============================

Fortigate devices allow to send their logs to a remote rsyslog server. I was looking for a logwatch plugin to observe these logs in a condensed view. Of course there are commercial solutions by Fortinet, but I use the device at home and therefore I was looking for a cheap solution. I didn't find anything appropriate, so this is a quick hack for a logwatch plugin. Maybe it will improve over time, but at the first glance I'm happy with it :-)


## CHANGELOG

2018-04-17: adapted expressions for FortiOS 5.6 log format
2017-11-27: initial release
