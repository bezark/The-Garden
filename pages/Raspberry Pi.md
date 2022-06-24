---
publish: true 
tags: [ ref/pcom, ref/linux ]
---

# Cons
[[Raspberry Pi]] is always running an OS so the feedback is always a little slower than  [[microcontrollers]]
- also no Analog Input
  
  [[Getting a Raspberry to Pull a Github Repo on Boot]]
  
  <iframe title="vimeo-player" src="https://player.vimeo.com/video/267634882" width="640" height="360" frameborder="0" allowfullscreen></iframe>
  
  
  **[Pi Recipes](https://tigoe.github.io/PiRecipes/)**
-
- [[pi Cam]]
# Setting Up a Pi
- [x] #todo Lookup Pi serial port adapter 📅 2021-12-20 ✅ 2021-11-14
  
  [Setting up a Raspberry PI  ITP Guide](https://itp.nyu.edu/networks/setting-up-a-raspberry-pi/) ^7babe9
  
  
  ![[First Attempt at Setting up a Raspberry Pi Host#Linux Caveat]]
  
  
  Use raspberry pi IMIGER
  
  ![Diagram showing USB-to-serial adapter connected to a Raspberry Pi through their respective transmit (TX) and receive (RX) pins. The adapter's ground pin is also connected to the Pi's ground pin.](https://itp.nyu.edu/networks/wp-content/uploads/2017/06/pi_serial_bb-1024x980.png){:height 988, :width 1024}
  
  Default login: pi
  Default password: raspberry
  
  ![Diagram identifying each of the I/O pin connections for the Raspberry Pi.](https://itp.nyu.edu/networks/wp-content/uploads/2017/06/pi_pinouts-503x1024.png)
  
  Advanced options -> Expand Filesystem gives access to the entire SD Card
  
  Wifi connects LOCALLY.... so using [[Hash functions]] 
  #question so how does wifi actually work?
  
  onoff [[Node|node.js]] library
  
  Most [[microcontrollers]] libraries are just fancy interfaces for [[SPI]] and [[I2C]]
  
  
  `CTRL-A CTRL-\` Quits `Screen`