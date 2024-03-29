# Pet Health Monitor Duo

## Introduction

The "Pet Health Monitor Duo" is an innovative, two-part system designed to keep a watchful eye on your pet's vital health statistics. It comprises a sensor-equipped pet collar and a dedicated display device. The collar, sleek and comfortable for your pet to wear, integrates advanced Pulse and LM-35 temperature sensors, while the display device features a clear LCD screen with LED indicators, ensuring you're always informed about your pet's well-being.

<img src="pics/pet%20collar.png" title="" alt="pet collar.png" width="406">



<img src="pics/LCE%20SCREEN%20AMAZON.jpg" title="" alt="LCE SCREEN AMAZON.jpg" width="412">



## Sensor Device

<img title="" src="pics/pulse.jpg" alt="" width="232" data-align="left">



<img src="pics/temp.jpg" title="" alt="temp.jpg" width="223">

The sensor device, embedded within a pet collar, uses a **Pulse Sensor** and an **LM-35 temperature** sensor connected to an **Arduino Uno** microcontroller. These sensors continuously monitor the pet's heart rate and body temperature. The collar's design ensures comfort for the pet while providing accurate and reliable data.

## Display Device





<img src="pics/LCE%20SCREEN%20AMAZON.jpg" title="" alt="LCE SCREEN AMAZON.jpg" width="346">
<img src="pics/screen.jpg" title="" alt="" width="292">

The display device is an **LCD screen** equipped with LED indicators. It communicates with the sensor device via Bluetooth, displaying real-time updates of your pet's heart rate and temperature. In case of any abnormalities, the LED lights flash as an alert, allowing for immediate attention and action.

## Microcontroller

<img src="pics/arduino.jpg" title="" alt="arduino.jpg" width="270">

The core of the sensor device in the "Pet Health Monitor Duo" is the Arduino Uno microcontroller. This microcontroller is the brain behind the pet collar and the screen.





#### 4. Communication Diagram and Functional Diagram



<img src="pics/diagram.png" title="" alt="diagram.png" width="270">

The devices communicate seamlessly through **Bluetooth** technology. The sensor device on the collar transmits health data to the display device, which then processes and displays the information. 

In case of any unusual readings (like a spike in temperature or heart rate), the display device's LED indicators will flash as an immediate warning signal. This system ensures that pet owners are always informed about their pet's health status and can respond promptly to any potential health concerns.