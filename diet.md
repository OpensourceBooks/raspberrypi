1. download dietpi

```
wget https://dietpi.com/downloads/images/DietPi_RPi-ARMv6-Stretch.7z
```

2. install ether.io

```
https://etcher.io
```

3. config wifi

Goto my computer, select the SD card and open it.
- Locate the file called dietpi.txt and open it with wordpad.
- Set AUTO_SETUP_NET_WIFI_ENABLED=1.
- Enter your ssid AUTO_SETUP_NET_WIFI_SSID=MySSID and AUTO_SETUP_NET_WIFI_KEY=MyWifiKey (both are case sensitive).
- Save the file.

4. Login to DietPi

- username = root
- password = dietpi
- DietPi also comes pre-installed with Dropbear SSH Server.
On first login, DietPi will automatically update. Once completed, press enter to reboot the system. You can log back in again to resume setup.
