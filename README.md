# Smart-Dustbin
IOT Based Project
Wiring:
1.VCC to Pin 2 (VCC)
2.GND to Pin 6 (GND)
3.TRIG to Pin 12 (GPIO18)
4.connect the 330Ω resistor to ECHO.  On its end you connect it to Pin 18 (GPIO24) and through a 470Ω resistor you connect it also to Pin6 (GND).

Packages:
sudo iwlist wlan0 scan
sudo pip install wifi 

How to run:

1. Create sudo nano ultrasonic_distance.py
2. Put the code which is in ds.py
3. Set the Wifi ssid & key
4. Now Run & it will show its work