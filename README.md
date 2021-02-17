# ESPHome-Inkplate-Family-Calendar
 Family Calendar application for the Inkplate6 running ESPHome
 
 <img alt="Screenshot of Inkplate Calendar" src="https://github.com/jkmaxwell/ESPHome-Inkplate-Family-Calendar/raw/main/README_images/screenshot.png" width="400">
 
# Prerequisites
- Home Assistant running
     - NodeRed w/Node-Red add-on (integration) in HA for API connectivity
     - ESPHome
- Inkplate6 (will support 10 when i get mine) w/[1200MaH](https://www.amazon.com/gp/product/B07BTSPZW8/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&psc=1) or higher Battery
- Patience and forgiveness for my shitty code

# Installation
- NodeRed
     - Import the NodeRed setup to a new pane and customize the google api variables and your calendar data. To do this you'll need to learn how those nodes work, which is a huge pain in the ass in itself and I wish you the best of luck.
- ESPHome
     - Add the folder structure in this repo within your /config/esphome dir on your HA install. You'll want to find fonts or customize the YAML to address the missing ones.
- Inkplate
     - I like using the CLI binary. Find the ESPHome-Flasher.app and put it in your applications folder. chmod as needed and then use it this way: `./ESPHome-Flasher.app/Contents/MacOS/ESPHome-Flasher -p /dev/tty.usbserial-310 /Users/you/dev/thisreponame/inkplate.bin`. To find your serial port, `ls -al /dev/tty*`.

# Support
None. This is mainly for me right now and not for you. If you're interested in trying it out and wish to collaborate, please contact me at @303 on twitter.
 
 
