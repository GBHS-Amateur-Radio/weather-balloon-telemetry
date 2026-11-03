
 ## Thermistor
 **Adafruit 10K Precision Epoxy Thermistor - 3950 NTC**
 
- [website](https://www.adafruit.com/product/372?srsltid=AU7gw4VnNkI3PNdCLb7qaMvomEU1S2Hzd0cGMylpWFV8qbJn_1rmWSBqpPA)
 [data sheet](https://www.adafruit.com/product/372?srsltid=AU7gw4VnNkI3PNdCLb7qaMvomEU1S2Hzd0cGMylpWFV8qbJn_1rmWSBqpPA)

- Measurement range: -55°C - 125°C

- Accuracy: The resistance at 25 °C is 10K (+- 1%). The resistance goes down as it gets warmer and goes up as it gets cooler.

- Power: Dissipation Constant - Approximately 2.0 mW/°C to 5.0 mW/°C Maximum; Power Rating - Typically around 45 mW to 50 mW (I had to find this on googleAI because I couldn't find it on the website?)

- Operating temp.: -55°C - 125°C

- Price: $4.00 each

     - On the adafruit website they have a tutorial on how to use this electronic w/ Arduino
 
**TMP36 - Temperature Sensor**

Aaron Price on Instructables [The Ultimate High Altitude Weather Balloon Data Logger](https://www.instructables.com/The-Ultimate-High-Altitude-Weather-Balloon-Data-Lo/) used this, one on the outside and one on the inside

[datasheet](https://dlnmh9ip6v2uc.cloudfront.net/datasheets/Sensors/Temp/TMP35_36_37.pdf)
[website](https://www.crcibernetica.com/tmp36-temperature-sensor/)

- Measurement range: −40°C to +125°C

- Accuracy: ±2°C accuracy

- Power: Voltage Input: 2.7 V to 5.5 VDC

- Operating temp.: −40°C to +125°C

- Price: $1.95

## Three Sensors in One
**Adafruit BME280 I2C or SPI Temperature Humidity Pressure Sensor**

- Temperature, humidity, pressure

- This was used by Oklahoma State University students in their [HAB project](https://www.iastatedigitalpress.com/ahac/article/17976/galley/16038/view/)

[website](https://www.adafruit.com/product/2652?gad_source=1&gad_campaignid=23986111167&gbraid=0AAAAADx9JvRt2OmR7Vv-wJR6BT2xGlrfr&gclid=CjwKCAjww-3VBhAcEiwAwUUIuy6uYw38ZogDRpBD7XNK4MSBwf0Ojrcu5RyWB6-BrnTFGoUtVUwO7hoCK6oQAvD_BwE)
[data sheet](https://cdn-learn.adafruit.com/assets/assets/000/115/588/original/bst-bme280-ds002.pdf?1664822559)

- Measurement range: -40-85°C, 0-100% rel. humidity, 200-1100hPa 

- Accuracy: <img width="1220" height="312" alt="image" src="https://github.com/user-attachments/assets/9c7f67ae-d424-49eb-a2df-c39b156b2e69" />
<img width="1190" height="124" alt="image" src="https://github.com/user-attachments/assets/14151d3c-234a-4048-ad2e-d8dbd5bed9cd" />

- Power: <img width="1222" height="174" alt="image" src="https://github.com/user-attachments/assets/94af73eb-d4cf-43f5-ac6e-f96d9f3884fe" />

- Operating temp.: -40-85 °C

- Price: $14.95

## Gyroscope/Acceleraometer 
**Adafruit LSM6DSO32 6-DoF Accelerometer and Gyroscope - STEMMA QT / Qwiic**

[website](https://www.adafruit.com/product/4692?gad_source=1&gad_campaignid=23986111167&gbraid=0AAAAADx9JvRt2OmR7Vv-wJR6BT2xGlrfr&gclid=CjwKCAjww-3VBhAcEiwAwUUIu8SdTH52Lnudb-l550WjRTsN14uxMrX_aO0w689KhVMC0LxuT8kjNhoC0UkQAvD_BwE )

- Henry Quach, Mechanical Engineer from Duke (all available information) used this in his weather balloon project as seen [here](https://henryquach.org/balloon.html)

- The following quotes are from the adafruit website

    - “This IMU sensor has 6 degrees of freedom - 3 degrees each of linear acceleration and angular velocity at varying rates..."
  
    - "For the accelerometer: ±4/±8/±16/±32 g at 1.6 Hz to 6.7KHz update rate."
 
    -  "For the gyroscope: ±125/±250/±500/±1000/±2000 dps at 12.5 Hz to 6.7 kHz."
  
    -  "There are also some nice extras, such as built-in tap detection, activity detection, pedometer/step counter, and a programmable finite state machine / machine learning core that can perform some basic gesture recognition.” 

    - "...you can use them with 3V or 5V power/logic devices without worry.” 

- No data sheet to be found

- Price: $12.50

## Ozonosonde

Quach, from the same page as above, used a [MQ131 Ozone Gas Sensor](https://www.winsen-sensor.com/product/mq131-h.html?campaignid=13060604585&adgroupid=120921749494&feeditemid=&targetid=kwd-707033075645&device=c&creative=520941455900&keyword=mq%20131&gad_source=1&gad_campaignid=13060604585&gbraid=0AAAAACTVC9Qb46alyjaH6-Ek96x9uH8RN&gclid=CjwKCAjww-3VBhAcEiwAwUUIu8EtJTj5XkayV2-pcV_acaAjVkF8SjrfmAqhvB7lUxgZDFGSfccpPBoCDFIQAvD_BwE)

price is hidden until you give them all your info

no data sheet I could find, just some specifications on the website
- detection range - 10-10000ppm (too high?)
- Loop Voltage 5.0V±0.1V DC
- Heater Voltage 5.0V±0.1V AC or DC 
- Heater consumption ≤950mW
- Sensitivity Rs(in 300ppm O3) / Rs(in air)≥2
- Output Voltage ≥1.0V (in300ppm O3) 

**EN SCI ECC Ozonesonde**
[website](https://www.en-sci.com/product/ecc-ozonesonde/)
- seems like a better, more official option
- Used by college students from Drexel Univ. on page 73 of this [document](https://drexel.edu/pennoni/~/media/Drexel/Pennoni-Group/Pennoni/Documents/UREP/STAR-Abstracts/2023-Abstract-Booklet.pdf)

- Measurement range: ppb (no range listed?)
- accuracy: ±5% at 1000, 100, and 10 hPa; ±10% at 4 hPa
- Operating pressure: 1050–4 hPa
- Operating temperature: 0–40°C
- External ambient temperature: −90 °C (it comes with its own insulted box I think)
- Power: 12–18 VDC, 120 mA

## Geiger Counter

DfRobot [Gravity: Geiger Counter Module Ionizing Radiation Detector](https://www.dfrobot.com/product-2547.html?srsltid=AU7gw4W0WOCaFGttAb-176eZ5pzJbXzDO3QE8H8v57008rzmpJogXzNk)


This affordable (...as it gets) option was used successfully by the researchers in this manuscript: [Testing Low-Cost Geiger Counters for Potential Use on Stratospheric Ballooning Missions](https://www.iastatedigitalpress.com/ahac/article/id/20147/)

Geiger Counter

Power Supply: 3.3V ~ 5V
Signal Output: digital output, pull down when pulse detected
Driving Voltage: ≈400V
Maximum Range: 1200 μSv/h(theoretically)
Outline Size: 107 x 42mm/4.21 x 1.65”


M4011 Geiger Tube

Operating Voltage: 380V ~ 450V
Background Counts: ≈25CPM
CPM Ratio: 153.8 CPM/(μSv/h)
Outline Size: Φ10mm x 88mm

Price: $60.00

## Cameras
Canon Powershot A1000IS used in this [Instructables](https://www.instructables.com/Barebones-High-Altitude-Balloon-Cam/?utm_source=chatgpt.com)

they had to "hack" it and "put the camera in endless time-lapse mode under its own power, simulating a half-shutter press to focus and then snapping a photo at intervals of a few seconds"

but this one is cheap, about 35$ second hand (find source)

I think the idea of taking a lot of pictures and putting them together as a video is advantageous

## Misc. Notes
Radiosonde *radio-sahnd* - group of things that collects data and transports it back to the ground

Many of the HABs I am reading about on Instructables/blogs are only using cameras and GPS, I am worried about the amount of sensors becoming too heavy or too accident prone, especially for the first balloon

Thermistor - Semiconductor resister that changes the number of electrons that move though a material sensitive to the temperature and easily predictable

NTC Thermistor (negative temperature coefficient) - type of resistor that the electrical conductivity decreases as temperature increases. Often used, not only for weather things 

Bead or epoxy-coated thermistor - water resistant and can often reach -60degC

Dissipation Constant - amount of power (mW) required to raise the thermistor's internal temperature by 1°C above environment. A higher constant means it is less prone to self-heating error

Maximum power rating - The absolute maximum amount of power the thermistor can safely handle

Beta (b) value/constant - A higher B value means the electrical resistance decreases sharply as the temperature rises, making the sensor more sensitive to small temperature changes (typical is like 4000k)

10K - The base resistance is 10,000 ohms
