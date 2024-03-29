# AQM-IOT
**Air Quality Monitoring(general):**

Air quality monitoring is a critical practice that involves the continuous assessment of the composition and cleanliness of the air in our environment. It plays a pivotal role in safeguarding public health and preserving the integrity of ecosystems. With the increasing prevalence of urbanization and industrialization, the quality of the air we breathe has become a growing concern.
Various air pollutants, such as particulate matter, gases like carbon monoxide and sulfur dioxide, and volatile organic compounds, pose significant threats to human well-being and the natural world. To address these challenges, a network of monitoring stations equipped with cutting-edge technology and Internet of Things (IoT) sensors has been established, enabling real-time data collection and analysis.
This data, transmitted to central servers, is processed and made accessible through user-friendly interfaces, offering citizens, policymakers, and environmental agencies the ability to monitor air quality trends, assess compliance with air quality standards, and make informed decisions. The Air Quality Index (AQI) serves as a simplifying metric, condensing complex air quality data into an easily understandable number.
Poor air quality is not only detrimental to public health, leading to respiratory illnesses and cardiovascular problems, but it also has profound environmental implications. It can harm ecosystems, damage crops and vegetation, and contribute to phenomena like acid rain. Air quality monitoring thus forms the basis for formulating regulations and policies to reduce emissions and mitigate air pollution's adverse effects. 
In this age of heightened environmental awareness, continuous and accurate air quality monitoring has become an essential tool for the protection of human health and the preservation of the planet's natural balance.
It serves as a beacon, guiding efforts to combat the challenges of air pollution and create a cleaner, healthier world for current and future generations.



**Project:**

In this project we are monitoring the air quality using iot sensors. This monitoring circuit is simulated online using tinkercad website and then the data is transmitted to thingspeak , a iot data entry platform where it retrieves data from tinkercad. 


**Components Required:**


Arduino Uno 

16X2 Charater LCD

ESP8266 Wi-Fi Module

MQ135 Gas Sensor


**Connections:**


LCD RS pin to digital pin 12

LCD Enable pin to digital pin 11

LCD D4 pin to digital pin 5

LCD D5 pin to digital pin 4

LCD D6 pin to digital pin 3

LCD D7 pin to digital pin 2

LCD R/W pin to ground

LCD VSS pin to ground

LCD VCC pin to 5V

10K resistor:

ends to +5V and ground

wiper to LCD VO pin (pin 3)


**DIAGRAM:**

![image](https://github.com/Sangeetha-44/AQM-IOT/assets/146975490/ebac59e1-ec5f-476c-a54a-d21ce7df4860)


**Software and Prerequisites**

Tinkercad.com: Tinkercad is an online platform for creating, simulating, and sharing electronic circuits. It's primarily used for educational and prototyping purposes.

Thingspeak.com: ThingSpeak is an IoT platform that allows you to collect, store, and analyze data from IoT devices. It's commonly used for IoT applications, data visualization, and remote monitoring.

