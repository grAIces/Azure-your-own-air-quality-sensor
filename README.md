# Azure your own air quality sensor 

Hi everyone! 

For those who skip intros:

In this tutorial you will learn how to:
- build an air quality measurement device from scratch,
- manage the sensor data in the cloud,
- predict air pollution levels.

First things first - we will start with a bit of IoT and Machine Learning - all of this connected to Azure Cloud. We want to show you how to build a simple air quality sensor that you can place in your house, garden or office building. 

Who can use this tutorial? Simply everyone. Regardless of your programming skills, you can either simply copy the code to your editor, or dig in it a bit, changing what you might find most suitable. 

In case of any issues or recommendations we would love to hear any input, contact us on our email adress: graices@outlook.com

# Getting the parts

Strting from scratch, first comes the brain so when it comes to the board we primarily used <a href="https://en.wikipedia.org/wiki/ESP8266"> ESP8266 Wifi Board </a> (just because we had it at hand) but also for some time played with <a href="https://www.sparkfun.com/products/13711"> SparkFun Thing Deveplopment Board </a>. Both worked well stacked on a basic <a href="https://www.digikey.com/catalog/en/partgroup/half-size-breadboard/71495"> Half-Size Breadboard </a>. When it comes to wiring we used nothing but the simplest <a href="http://www.hobbytronics.co.uk/breadboard-wire"> Single Core Breadboard Wires</a>.

We used analog sensors for the straight forward easy-to-go cable wiring (and the vintage feel). If you would want to play with digital sensors - we'd love to hear about your results.

For this tutorial we used recommended sensors from our fellow Microsft employee who built this sort of sensor and gave us the idea with his blog post. We used as follows:

1. Adafruit CCS811 Air Quality Sensor Breakout - VOC and eCO2 Sensor <br> 
<a href="https://www.adafruit.com/product/3566"><img src="/img/adafruit.jpg" width="400"/></a> <br>

* If you're living in Europe (like us) be prepared to wait - cause it only ships from USA and as we learned it is not a very reliable piece of equipment.
* We would recommend buying at least two at the start if one does not seem to work (happened to us). Better to spend extra $20 for second sensor at the start, than waiting another week for the second sensor to get shipped. 
* Maybe we will find a better replacement (or random recommendation) for the future. 

2. DHT11 – Temperature and Humidity Sensor <br> 
<a href="https://components101.com/dht11-temperature-sensor"><img src="/img/dht11.png" width="400"/></a>

* Cheap, good, reliable and easy to use
* You can buy practically anywhere, sometimes even in quantity not-less-than.

3. Nova PM 2.5 and PM 10 Sensor <br> 
<a href="https://www.aliexpress.com/item/32606349048.html"><img src="/img/nova-pm.jxr" width="400"/></a>

* For the most important dust particles: less than 2.5mm and 10mm.
* Has USB port and you can get input to the laptop directly if you would only want to play with this sensor only


