# PUSH-BUTTON-COUNTER

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: VIVEK KAMBLE

*INTERN ID*: CT04DZ256

*DOMAIN*: EMBEDDED SYSYTEMS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*PROJECT DESCRIPTION*:

Project Title:

Use a Temperature Sensor to Read and Display Temperature Data on an LCD or Serial Monitor

1. Software Tools Used

The main software platform for this project is the Arduino IDE, used for writing, compiling, and uploading code to the microcontroller. The IDE supports C/C++ programming and includes built-in libraries for sensor and display interfacing.

For digital sensors such as DS18B20, the OneWire and DallasTemperature libraries are used to communicate via the OneWire protocol and obtain precise temperature readings. For LCD displays with an I²C interface, the LiquidCrystal_I2C library simplifies communication using only two pins (SDA, SCL).

The Serial Monitor within Arduino IDE is used to display temperature readings on a computer screen for testing and debugging. Additionally, the Tinkercad Circuits Simulator is used for virtual circuit design and block code simulation before implementing the hardware.

The project’s objective is to measure ambient temperature using a sensor and display it on a 16×2 LCD or via the Serial Monitor.

The hardware includes an Arduino Uno (or similar microcontroller), a temperature sensor (LM35, TMP36, or DS18B20), and an LCD module. The sensor is connected to the Arduino through either an analog or digital pin, depending on the type.

Working Principle:

For analog sensors like LM35, the Arduino reads the sensor’s voltage output using analogRead() and converts it to temperature. LM35 outputs 10 mV per °C, so the conversion formula is:

Temperature\ (°C) = \frac{Analog\ Value \times 5.0 \times 100}{1024}

Process Flow:

1. Initialize the LCD and temperature sensor in the setup section.

2. Read temperature data from the sensor at regular intervals.

3. Convert the data into Celsius and optionally Fahrenheit.

4. Display the result on the LCD and/or send it to the Serial Monitor.

*Applications* :

This temperature monitoring system has various practical uses:

1. Environmental Monitoring – For homes, offices, and agricultural setups to track ambient temperature.

2. HVAC Control – In heating, ventilation, and air conditioning systems.

3. Food Storage – For monitoring refrigerators and freezers to ensure safe storage conditions.

4. Industrial Process Control – Maintaining operational safety in temperature-sensitive manufacturing processes.

5. Weather Stations – As a component of a multi-sensor weather monitoring setup.

6. IoT Smart Homes – Sending temperature data to online dashboards or mobile apps.

*Conclusion*:

This project demonstrates the interfacing of a temperature sensor with a microcontroller for real-time monitoring and display. It uses simple hardware, easily available libraries, and can be simulated in Tinkercad before actual implementation. The system is low-cost, easy to build, and forms a base for advanced IoT or automation projects.








