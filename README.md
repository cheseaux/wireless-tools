<b>RSSI-based smartphone geolocation using flying robots</b>

This project aims to geolocalize people by analyzing the Probe Request packets sent by their smartphone, when the Wifi is turned on. The sniffer interfaces (Wifi dongle with monitor mode enabled) are placed on flying robots for the purpose of this project, but they could be attach to any vehicle or fixed station.

It is a Master semester project conducted at EPFL, don't hesitate to take a look at the presentation's slides <a href="http://www.jonathancheseaux.ch/files/RSSI-Geolocation-slides.pdf">here</a>.

For more information or questions, you can contact me at cheseauxjonathan@gmail.com

<b>Usage</b>
On the plane :
```bash
<gpsfeeder> | ./PlaneSniffer <planeID> <mon_interface> <log_file_path>
```
On the base station :
```bash
./ThreadedServer
```
Live map : ../server/index.html

Replay framework : ../server/replay.html

<b>Dependencies</b>

Scapy - http://www.secdev.org/projects/scapy/

Tornado - http://www.tornadoweb.org/en/stable/
