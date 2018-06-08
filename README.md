# loragw_leds

1. login over ssh
2. $ git clone https://github.com/ensembletechindia/loragw_leds.git ~/wifi-leds
3. $ sudo crontab -e
4. in the menu choose nano
4. add the following line
  
    @reboot sudo python /home/ttn/wifi-leds/rpi-internet-monitor.py
