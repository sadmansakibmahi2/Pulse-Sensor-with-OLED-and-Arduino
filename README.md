
# Pulse Sensor with OLED and Arduino
 In this project, we will learn how to design ECG Display using Pulse Sensor with OLED & Arduino. We will use 0.96″ OLED Display with 128x64 resolution for BPM & ECG waveform display. The I2C OLED uses only 2 wire, i.e SDA & SCK for serial communication.

The Arduino Sketch running over the device implements the various functionalities of the project. These functions are reading sensor data, converting them into strings, passing them to I2C communication, and displaying measured pulse rate in I2C OLED Display.



## License

[MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)



## Software Used in this project

Please Install this software

[Arduino IDE](https://www.arduino.cc/en/software)

## library requirements

Please download the libraries

[adafruit ssd1306](https://github.com/adafruit/Adafruit_SSD1306)

[Adafruit GFX Library](https://github.com/adafruit/Adafruit-GFX-Library)


### Installing the zip library:-

    1) Download the .zip library to your PC.
    2) Open Arduino IDE.
    3) On Arduino IDE, Go to Sketch Include Library Add . ZIP Library...
    4) Select the downloaded .zip file, and then the library will be installed.
    5) Copy the above code and open with Arduino IDE.

## Components


[Pulse Sensor](https://techshopbd.com/detail/3192/Pulse_Sensor_(China)_techshop_bangladesh)

[ARDUINO](https://techshopbd.com/browse/search?term=Arduino%20uno)

[OLED Display](https://techshopbd.com/detail/2711/OLED_Display_Blue_I2C_128x64_0.96_inch_techshop_bangladesh)

[Buzzer](https://techshopbd.com/detail/3637/Passive_Buzzer_techshop_bangladesh)

[Male To Female Jumper Wire](https://techshopbd.com/detail/1135/Male_To_Female_Jumper_Wire_-_Single_techshop_bangladesh)

### Components Introduction:-

#### Arduino:-

Arduino is an open-source physical computing platform based on a simple I/O board and a development environment that implements the Processing/Wiring language. Arduino can be used to develop stand-alone interactive objects or can be connected to software on your computer (e.g. Flash, Processing and MaxMSP). The boards can be assembled by hand or purchased preassembled; the open-source IDE can be downloaded for free at https://arduino.cc

<img width="60%" img hight="60%" src="https://github.com/sadmansakibmahi2/Pulse-Sensor-with-OLED-and-Arduino/blob/main/Images/arduino.jpg">

#### Pulse Sensor:-

The Heartbeat rate information knowing is very useful while doing exercise, studying, etc. But, the heartbeat rate can be complicated to calculate. To overcome this problem, the pulse sensor or heartbeat sensor is used. This is a plug & play sensor mainly designed for Arduino board which can be used by makers, students, developers, artists who can utilize the heartbeat information into their projects. This sensor uses an easy optical pulse sensor along with amplification & cancellation of noise to make a circuit. By using this circuit, we can get fast and reliable heartbeat readings. This circuit can be operated with 4mA current and 5V voltage to use in mobile applications.

What is the Pulse Sensor?

An alternate name of this sensor is heartbeat sensor or heart rate sensor. The working of this sensor can be done by connecting it from the fingertip or human ear to Arduino board. So that heart rate can be easily calculated.The pulse sensor includes a 24 inches color code cable, ear clip, Velcro Dots-2, transparent stickers-3, etc.

 1) A color code cable is connected to header connectors. So this sensor is easily connected to an Arduino into the project without soldering.

 2) An ear clip size is the same as a heart rate sensor and it can be connected using hot glue at the backside of the sensor to wear on the earlobe.

 3)Two Velcro dots are completely sized toward the sensor at the hook side. These are extremely useful while making a Velcro strap to cover approximately a fingertip. This is used to cover the Sensor around the finger.

 4)Transparent strikers are protection layers used to protect the sensor from sweaty earlobes and fingers. This sensor includes three holes in the region of the external edge so that one can easily connect anything to it.

<img width="60%" img hight="60%" src="https://github.com/sadmansakibmahi2/Pulse-Sensor-with-OLED-and-Arduino/blob/main/Images/pluse%20sensor.jpg">

#### OLED Display 0.96 inches:-

2.44 cm (0.96 inch)  OLED Display Module is a precise small, White OLED module which can be interfaced with any microcontroller using SPI protocol. It is having a resolution of 128x64. The package includes display board, display, 6 pin male header.OLED (Organic Light-Emitting Diode) is a self light-emitting technology composed of a thin, multi-layered organic film placed between an anode and cathode. In contrast to LCD technology, OLED does not require a backlight. OLED possesses high application potential for virtually all types of displays and is regarded as the ultimate technology for the next generation of flat-panel displays.OLEDs basic structure consists of organic materials positioned between the cathode and the anode, which is composed of electric conductive transparent Indium Tin Oxide (ITO). The organic materials compose a multi-layered thin film, which includes the Hole Transporting Layer (HTL), Emission Layer (EML) and the Electron Transporting Layer (ETL). By applying the appropriate electric voltage, holes and electrons are injected into the EML from the anode and the cathode, respectively. The holes and electrons combine inside the EML to form excitons, after which electro luminescence occurs. The transfer material, emission layer material and choice of electrode are the key factors that determine the quality of OLED components.It can be used with either an spi  interface - selectable by soldering two jumpers on the again. The design is completely 5v-geared up, with an onboard regulator and constructed in raise converter. It's easier than ever to connect immediately for your 3v or 5v microcontroller without having any type of stage shifter.

<img width="60%" img hight="60%" src="https://github.com/sadmansakibmahi2/Pulse-Sensor-with-OLED-and-Arduino/blob/main/Images/oled%20display.jpg">

## Connections:-

### PULSE SENSOR CONNECTIONS:

| PULSE SENSOR PIN | ARDUINO PIN |
| ------------- | ------------- |
|  VCC | PIN 5V  |
| GND  | GND |
|  signal pin | A0  |



### OLED DISPLAY CONNECTIONS:

| OLED DISPLAY | ARDUINO PIN |
| ------------- | ------------- |
| VCC   | 3.3V  |
| GND   | GND |
| SDA | A4   |
| SCK  | A5  |

### Note:
For some OLED there is a problem with the trace being at the bottom and the BPM being missing then this is caused by the following lines in the Adafruit_SSD1306.h file in your libraries folder :

#define SSD1306_128_64

// #define SSD1306_128_32

// #define SSD1306_96_16

## Programing The Arduino:-
Copy the code from this link

[Code](https://github.com/sadmansakibmahi2/Pulse-Sensor-with-OLED-and-Arduino/blob/main/Arduino%20code/code.ino)

Now compile and upload this code to your Arduino IDE.

Your project is now ready.


## Author

- [sadmansakibmahi2](https://www.github.com/sadmansakibmahi2)


