LapsePiTouch
============

Touchscreen Timelapse controller for Raspberry Pi and Adafruit PiTFT by [David Hunt](http://www.davidhunt.ie) 

Based on code by PaintYourDragon (Phil B) for Adafruit Industries

Read more about this project at [Dave's Blog](http://www.davidhunt.ie/?p=3349)

Enjoy!

![LapsePi Touch](http://i.imgur.com/0LiKRwd.jpg)

**Prerequisites:**

You must have gone through the [Adafruit PiTFT setup instructions](http://learn.adafruit.com/adafruit-pitft-28-inch-resistive-touchscreen-display-raspberry-pi).

You must have gone through the [WiringPi-Python Setup instructions](https://github.com/WiringPi/WiringPi-Python).

**Get repo:**
    
    git clone https://github.com/Artsonic/LapsePiTouch.git
    
    
**Usage:**

    cd LapsePiTouch

    sudo python lapse.py
	
Once youve got that working, have the Pi boot straight into the time-lapse software by editing /etc/rc.local and adding the following lines before exit 0

	cd /home/pi/LapsePiTouch

	python lapse.py


Full details at: [Dave's Blog](http://www.davidhunt.ie/?p=3349)

If you would like to donate to the Lapse Pi Touch project to keep it active you can do so via [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=Y3Y6NK98CZUZW)
