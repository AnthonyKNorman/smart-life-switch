# smart-life-switch
## Re-flashing a Smart Life Switch with ESPHome for Home Assistant
The aim with all of my smart home devices is to use only my internal cloud to prevent sharing my activities with some unknown web site. I bought this Smart WiFi dual wall switch from https://www.aliexpress.com/. It is one of these clever ones that doesn't need a Neutral wire. 

<p align="center">
  <img width="200" src="resources/IMG_0263.jpg">
  <img width="200" src="resources/IMG_0264.jpg">
</p>

At the time of writing, tuya-convert was broken because of a fix in the TUYA firmware, so hardware flashing was the only option.
I have done this many times, and, as the photo shows, the TYWE3S ESP8266 module is very exposed and easy to access for soldering. This should have been easy. 
<p align="center">
  <img width="200" src="resources/IMG_0265.jpg">
</p>
I soldered wires to Tx, Rx, Vcc and GND. I connected GPIO0 to GND. 
