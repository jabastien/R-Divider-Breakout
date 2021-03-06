Voltage divider breakout for 4 Channels ADS1015/ADS1115 ADC Board
=================================================================

This shield is used to decrease voltage input when it's higher than the embeded device can hold. For example with 3.3V devices we can't hold input W 3.3V and measuring for example Lipo Battery or Solar Panel voltage is not possible.
This board indroduce 
- 4 voltage divider 
- I2C ADS1x15 board compatible for devices that do not have enought ADC such as [WeMos][1]
- Footprint for 0805 caps for filtering input.

This board can fit on Adafruit [ADS1115][5] or [ADS1015][6] 
<img src="https://raw.githubusercontent.com/hallard/R-Divider-Breakout/master/pictures/ads1115.png" alt="ADS1115">

**In this case take care to just connect A0..A3 and GND to Adafruit board when stacking** other Adafruit board pins are used for input on my breakout.

**Waiting Boards from PCBs.io and OSHPark, I did not fully tested them yet, I will update ASAP. Use at your own risks**

Detailed Description
====================

Look at the schematics for more informations.

### Schematic
![schematic](https://raw.githubusercontent.com/hallard/R-Divider-Breakout/master/pictures/R-Divider-Breakout-sch.png)  

### Boards 
<img src="https://raw.githubusercontent.com/hallard/R-Divider-Breakout/master/pictures/R-Divider-Breakout-top.png" alt="Top">

<img src="https://raw.githubusercontent.com/hallard/R-Divider-Breakout/master/pictures/R-Divider-Breakout-bot.png" alt="Bottom"> 

### Received boards

<img src="https://raw.githubusercontent.com/hallard/R-Divider-Breakout/master/pictures/R-Divider-pcb.jpg" alt="PCB"> 


You can order the PCB of this board at [OSHPARK][4] or at [PCBs.io][3].
PCBs.io give me some reward when you order my designed boards from their site. This is pretty cool because I can use these rewards to create and design new boards and order boards for a discounted price, so if you don't care about PCB manufacturer please use PCBs.io.

### Assembled boards

Here is a picture of assembled board stacked with an ADS1115 ADC breakout

<img src="https://raw.githubusercontent.com/hallard/R-Divider-Breakout/master/pictures/R-Divider-mounted.jpg" alt="Mounted boards"> 

Take care when stacking, analog Input of breakout should not be connected to ADS1115 dedicated I2C and ADC control line, you'll need to use on long pin connector as follow

<img src="https://raw.githubusercontent.com/hallard/R-Divider-Breakout/master/pictures/R-Divider-stacked.jpg" alt="Mounted and stacked with ADS1115 board"> 

<img src="https://raw.githubusercontent.com/hallard/R-Divider-Breakout/master/pictures/R-Divider-connector.jpg" alt="Long pin connector"> 


##License

You can do whatever you like with this design.

##Misc
See news and other projects on my [blog][1] 
 
[1]: http://www.wemos.cc/Products/d1_mini.html
[2]: https://hallard.me
[3]: https://PCBs.io/share/rJ1B8 
[4]: https://oshpark.com/shared_projects/vyab8UWr
[5]: https://www.adafruit.com/product/1085
[6]: https://www.adafruit.com/products/1083
