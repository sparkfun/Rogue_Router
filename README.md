# Rogue_Router

Solar Access Point Fileserver for SparkFun Thing
Featured here: https://www.sparkfun.com/news/2009

*3D Files* - Models for 3D Printed Enclosure

*Firmware* - SDAPServer code for SparkFun Thing

*Img* - Pics of the enclosure

## Firmware Versions

### SDAPServer

...is a sloppy amalgam of SDWebServer and WiFiAccessPoint, orginially from Hristo Gochkov.


### SDAPServerCaptive

...is a sloppy amalgam of SDWebServer and WiFiAccessPoint with some DNSServer thrown in to add Captive Portal functionality. 

Captive Portal modifications are dependant on latest DNSServer library via: 
https://github.com/knovoselic/Arduino/tree/dns_server_improvements/hardware/esp8266com/esp8266/libraries/DNSServer
with patch by "blackie" from:
http://www.esp8266.com/viewtopic.php?f=32&t=3618&start=36#p21726

No SSL Support yet :( So https:// adresses are not redirect. Traffic is rejected. 

## Enclosure Versions

### Rogue1 

...is the version shown in the video.

![Rogue1](https://raw.githubusercontent.com/sparkfun/Rogue_Router/master/Img/Rogue1.jpg)

### Rogue1.2 

...has an updated enclosure with snap-in standoffs and SD instead of uSD. 

![Rogue1.2](https://raw.githubusercontent.com/sparkfun/Rogue_Router/master/Img/Rogue1.2_closeup.jpg)

![Rogue1.2b](https://raw.githubusercontent.com/sparkfun/Rogue_Router/master/Img/Rogue1.2.jpg)

### Rogue Mini

...is very very small and does not incorporate solar charging

![RogueMini](https://raw.githubusercontent.com/sparkfun/Rogue_Router/master/Img/RogueMini.jpg)
