# Parking Lot Counter Using Digital Electronics

**INTRODUCTION**

A parking lot has definite number of spaces in which the cars can occupy. Once the parking lot is full, other cars do not have space to occupy. To indicate the number of occupied spaces in the parking lot an indicator is used.

This is a project on a simple parking lot counter. This simple circuit can be used to count the number of cars entering and exiting a parking lot. We need to monitor the number of occupied slots in the parking area by setting up proximity1 sensor at the entrance whereas the output of this sensor is high(1) when a car is entering the parking area. On the other hand proximity2 sensor is allocated in exit. The output of the sensor is high(1) when there is a car leaving the parking area. By calculating these values we can determine the number of occupied spaces.

<br/>

**BLOCK DIAGRAM**

![Aspose Words e7bf79d2-d533-4075-a14c-66c8496837b0 001](https://github.com/sourabhshanbhogue/ParkingLot_Counter/assets/84284202/31f167fc-d99c-49e5-bcb5-ad608b564b2e)

<br/>

**CIRCUIT DESIGN**

![Aspose Words e7bf79d2-d533-4075-a14c-66c8496837b0 002](https://github.com/sourabhshanbhogue/ParkingLot_Counter/assets/84284202/a7a1ea19-ad0a-4ed8-bd0a-5fda18bcb7c8)


The above mentioned is the circuit diagram of a simple parking lot counter.

Note\*: The circuit of IR Module is not mentioned in this diagram. In place of it, an interactive input is placed. While constructing the circuit replace the proximity with IR sensor Module.

<br/>

**TEST PROCEDURE**

1. Circuit connections are done as shown in the circuit diagram.
2. VCC and GND are given to appropriate IC pins.

To check maximum capacity of the parking lot:

1. An obstacle is brought near Proximity 1 until the led on the module glows.
2. An Up count is observed on the 7 segment display
3. Repeat steps 3 and 4, eight more times.
4. The full indicator Led glows when 9 is displayed on the seven segment display.

To check display count when cars leave the parking lot:

1. An obstacle is brought near Proximity 2 until the led on the module glows.
2. A down count is observed on the 7 segment display.

<br/>

**RESULTS**

![Aspose Words e7bf79d2-d533-4075-a14c-66c8496837b0 014](https://github.com/sourabhshanbhogue/ParkingLot_Counter/assets/84284202/2ca79ae5-1c45-418a-9318-5fa29c718b3a)

The parking lot counter circuit diagram is implemented and outputs are verified.
