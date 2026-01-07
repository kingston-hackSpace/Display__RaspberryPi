# Display__RaspberryPi

Raspberry Pi can work with a wide range of display screens. Below is a list of suitable types:

----
## HDMI Displays

Standard monitors and televisions with HDMI input. These displays support high resolutions and provide the best performance for desktop use, multimedia, and graphical applications.

**Can run:** Video, full graphics, desktop applications, animations, games

----
## OLED Display

Small displays that use OLED technology, offering very high contrast and sharp text. They are typically low resolution and are commonly connected via I²C or SPI.

**Can run:** Simple graphics, text, basic animations.

**Cannot realistically run:** Full-motion video.

----
## GPIO - LCD TFT Display

Compact colour displays that connect via the RPi GPIO pins (often using SPI) and often include touch input. Using GPIO means some pins are occupied, which may limit adding extra sensors or devices.

**Can run:** Basic graphics, simple GUI, small animations.

**Cannot realistically run:** Full-motion video smoothly.

Read more [here]

----
## DSI ribbon connection - LCD TFT Display

Displays specifically designed for Raspberry Pi that use the DSI (Display Serial Interface) ribbon cable. Because the display does not use the GPIO pins, they remain available for connecting sensors, actuators, and other external devices.

**Can run:** Basic graphics, simple GUI, small animations.

**Cannot realistically run:** Full-motion video smoothly.

----
## RGB Matrix Display

Large panels made up of individually addressable RGB LEDs, capable of displaying text, animations, and graphics.

**Can run:** Text, animations, scrolling graphics, simple games.

**Cannot realistically run:** Standard videos or complex graphics.

Read more [here](https://github.com/kingston-hackSpace/rgb_led_displays?tab=readme-ov-file)

----
## E-paper Display

Small sisplays that mimic paper, using e-ink technology. Colour limited. 

**Can run:** Static images, text, charts

**Cannot realistically run:** Videos, fast animations


