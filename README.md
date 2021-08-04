## Adafruit DS3231 Precision RTC Breakout PCB
<a href="http://www.adafruit.com/products/5188"><img src="assets/5188.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a><br/>
<a href="http://www.adafruit.com/products/3013"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

The datasheet for the DS3231 explains that this part is an "Extremely Accurate I²C-Integrated RTC/TCXO/Crystal". And, hey, it does exactly what it says on the tin! This Real Time Clock (RTC) is the most precise you can get in a small, low power package.

Most RTCs use an external 32kHz timing crystal that is used to keep time with low current draw. And that's all well and good, but those crystals have slight drift, particularly when the temperature changes (the temperature changes the oscillation frequency very very very slightly but it does add up!) This RTC is in a beefy package because the crystal is inside the chip! And right next to the integrated crystal is a temperature sensor. That sensor compensates for the frequency changes by adding or removing clock ticks so that the timekeeping stays on schedule.

This is the finest RTC you can get, and now we have it in a compact, breadboard-friendly breakout. With a coin cell plugged into the back, you can get years of precision timekeeping, even when main power is lost. Great for datalogging and clocks, or anything where you need to really know the time.

PCB files for the Adafruit DS3231 Precision RTC Breakout. The format is EagleCAD schematic and board layout
- https://www.adafruit.com/products/3013

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional information.
