Carputer
====

I want a car computer. My phone works (somewhat) to play music or do navigation,
but I'd like to have something I've got a bit more control over. And for longer
trips, I don't want to have to rely on my phone.

Also, it seems like it'd be a fun project.

Still in the planning stages right now.

# Other Projects To Crib From
* [NoamdicPi](https://www.nomadicpi.com/get-started.php) [Other Link](https://www.hackster.io/anthony-mills/nomadic-pi-car-computer-5735f1)
* 

# Hardware

* [Raspberry Pi 3 B+](https://www.sparkfun.com/products/14643)
* [Raspberry Pi LCD - 7" Touchscreen](https://www.sparkfun.com/products/13733)
* [SmartPi Touch](https://www.sparkfun.com/products/14059)
* [SparkFun Venus GPS](https://www.sparkfun.com/products/11058)
* [Antenna GPS3V Magnetic Mount SMA](https://www.sparkfun.com/products/464)
* [More hardware ideas](https://www.raspberrypi.org/forums/viewtopic.php?t=70517)
* [Raspberry Pi Zero W](https://www.sparkfun.com/products/14298)
* [Bluetooth USB Module](https://www.sparkfun.com/products/9434)
* [other usb blueooth modules](https://www.amazon.ca/s/ref=nb_sb_noss_2?url=search-alias%3Daps&field-keywords=usb+bluetooth&rh=i%3Aaps%2Ck%3Ausb+bluetooth)
* [wifi usb](https://www.amazon.ca/TP-Link-TL-WN725N-Wireless-Adapter-Miniature/dp/B008IFXQFU/ref=sr_1_2?ie=UTF8&qid=1527574429&sr=8-2&keywords=wifi+usb)
* [more wifi usb](https://www.amazon.ca/AmazonBasics-Wi-Fi-Nano-Adapter-Black/dp/B06XSFPDFX/ref=sr_1_3?ie=UTF8&qid=1527574429&sr=8-3&keywords=wifi+usb)  
* [even more wifi usb](https://www.amazon.ca/PLLMOKKO-Portable-Adapter-Wireless-Applicable/dp/B078G1VPHK/ref=sr_1_6?ie=UTF8&qid=1527574471&sr=8-6&keywords=usb+802.11n)
* [more gps](https://www.amazon.ca/Adafruit-Ultimate-GPS-Breakout-External/dp/B00I6LZW4O/ref=pd_sim_504_7?_encoding=UTF8&pd_rd_i=B00I6LZW4O&pd_rd_r=7e42034e-630d-11e8-8ce9-a3e8d727e07b&pd_rd_w=sMfob&pd_rd_wg=Ey4MO&pf_rd_i=desktop-dp-sims&pf_rd_m=A3DWYIK6Y9EEQB&pf_rd_p=818483864814972661&pf_rd_r=G7XJJPEGMRAMAKQ6EQCQ&pf_rd_s=desktop-dp-sims&pf_rd_t=40701&psc=1&refRID=G7XJJPEGMRAMAKQ6EQCQ)  


# Software

* [GPSD](http://www.catb.org/gpsd/) - to handle getting GPS data from the GPS device ( [client docs](http://www.catb.org/gpsd/client-howto.html) )
* [Go-GPSD](https://github.com/stratoberry/go-gpsd) - Go client to GPSD
* [MoNav](https://wiki.openstreetmap.org/wiki/MoNav) OSM navigation software
* [Navit](https://github.com/navit-gps/navit) - pretty good-looking navigation software
* [More Navit stuff on the wiki](http://wiki.navit-project.org/index.php/Raspberry_Pi)
* [Tangram](https://www.raspberrypi.org/blog/tangram-an-open-source-map-rendering-library/) - another potential
* [Adafruit Ultimate GPS on the Raspberry Pi](https://learn.adafruit.com/adafruit-ultimate-gps-on-the-raspberry-pi/setting-everything-up)

# DevOps

* [Packer Build ARM Image](https://github.com/solo-io/packer-builder-arm-image) - use to build image for Raspberry Pi
* [Cross Compile Go for RPi](https://www.thepolyglotdeveloper.com/2017/04/cross-compiling-golang-applications-raspberry-pi/) 
* [Open Browser Full Screen](https://raspberrypi.stackexchange.com/questions/69204/open-chromium-full-screen-on-start-up)


# References
* [SparkFun OBD II](https://learn.sparkfun.com/tutorials/getting-started-with-obd-ii)

# Audio Stuff
* https://www.raspberrypi.org/magpi/raspberry-pi-fm-transmitter/
* https://howtoraspberrypi.com/create-radio-transmitter-raspberry-pi/
* http://www.instructables.com/id/Raspberry-Pi-Wireless-Bluetooth-Audio-FM-Radio-Tra/
* http://www.instructables.com/id/Turn-your-Raspberry-Pi-into-a-Portable-Bluetooth-A/  
* https://www.amazon.ca/s/ref=nb_sb_noss_2?url=search-alias%3Daps&field-keywords=Bluetooth+A2DP
* https://howtoraspberrypi.com/create-radio-transmitter-raspberry-pi/

# Other Hardware
* https://www.amazon.ca/Aukru-Charger-3000mA-Supply-Raspberry/dp/B019SX6UQ2/ref=sr_1_2?ie=UTF8&qid=1527575851&sr=8-2&keywords=USB+5v+3000mA+raspberry+pi
* [alternate case](https://www.amazon.ca/Raspberry-Pi-7-Inch-Touch-Screen/dp/B01GQFUWIC/ref=pd_sim_504_6?_encoding=UTF8&pd_rd_i=B01GQFUWIC&pd_rd_r=7e42034e-630d-11e8-8ce9-a3e8d727e07b&pd_rd_w=sMfob&pd_rd_wg=Ey4MO&pf_rd_i=desktop-dp-sims&pf_rd_m=A3DWYIK6Y9EEQB&pf_rd_p=818483864814972661&pf_rd_r=G7XJJPEGMRAMAKQ6EQCQ&pf_rd_s=desktop-dp-sims&pf_rd_t=40701&psc=1&refRID=G7XJJPEGMRAMAKQ6EQCQ)
*   

# Power
* https://www.amazon.ca/Griffin-PowerJolt-Universal-Charger-ChargeSensor/dp/B00BIGFJ24/ref=sr_1_fkmr0_1?ie=UTF8&qid=1527576829&sr=8-1-fkmr0&keywords=POWERJOLT+UNIVERSAL+WITH+CHARGESENSOR+10+WATT
* more: https://www.amazon.ca/s/ref=nb_sb_noss_2?url=search-alias%3Delectronics&field-keywords=car+charger+usb+
* https://www.amazon.ca/Hardwire-Micro-Supply-Raspberry-DURAGADGET/dp/B008OVL4E8

# Other Things
* https://www.raspberrypi.org/forums/viewtopic.php?f=66&t=133691
* [touchscreen setup](https://learn.adafruit.com/adafruit-pitft-28-inch-resistive-touchscreen-display-raspberry-pi/console-configuration)



