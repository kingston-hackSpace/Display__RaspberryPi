# GPIO - LCD TFT Display

The following screens are available at hackSpace:

----
# 3.5'' LCD TFT Display

See reference image [here](https://github.com/kingston-hackSpace/Display__RaspberryPi/blob/main/LCD_Elegoo_1.jpg)

The 3.5'' LCD TFT Display module was designed for use with Raspberry Pi boards. It offers a 480 × 320 pixel colour display with an integrated resistive touch panel, making it suitable for small graphical interfaces and DIY projects. The screen connects via the Pi’s GPIO pins using an SPI interface, so it doesn’t use HDMI and leaves most GPIO free for other hardware. It typically includes a simple touch stylus and requires a compatible driver to appear as the console display on the Pi.

----
### Features

  - Runs videos (.mov, .mp4) at low framerate and low resolution. Not suitable for smooth or high-quality video
    
  - Typical performance:
      
      - 5–15 FPS

      - Best at 320×240 or 480×32

### Wiring

Wiring reference image [here](https://github.com/kingston-hackSpace/Display__RaspberryPi/blob/main/LCD_Elegoo_3.png)


### Driver Installation Instructions:

  - If you are running this screen for the first time in your RPi, you will need to install a driver that allows communication between the devices.

  - To install the driver, connect your RPi to a keyboard, mouse and screen via HDMI.

  - Turn on your RPi

  - Open the Terminal and type:

    ```
    sudo apt update
    sudo apt install git
    git clone https://github.com/goodtft/LCD-show.git
    cd LCD-show/
    sudo ./LCD35-show
    ```
  - The Pi will reboot automatically. 

For further details, download manual [here](https://github.com/kingston-hackSpace/Display__RaspberryPi/blob/main/35_tft.pdf)

----




