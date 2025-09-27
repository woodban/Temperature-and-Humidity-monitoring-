# ☁️ IoT-Based Humidity and Temperature Monitoring using NodeMCU

## Abstract

This project describes an **IoT-based system** for real-time monitoring of temperature and humidity. It utilizes the **NodeMCU ESP8266** microcontroller, a **DHT11 sensor**, and the **ThingSpeak cloud platform** to create a smart environmental monitoring solution. The system continuously measures environmental conditions and sends the real-time data to the internet via Wi-Fi. This data can then be accessed and monitored remotely via a web dashboard where ThingSpeak visualizes the readings in graphs. The data is updated every **5-15 seconds**, allowing users to easily analyze trends and climate conditions over time. This system is a cost-effective, scalable solution useful for weather stations, agriculture, smart homes, and industrial applications.

---

## Components and Materials

The following apparatus is required for this project:

| Component | Description |
| :--- | :--- |
| **NodeMCU ESP8266** | Wi-Fi-based microcontroller used to process data and transmit it to the cloud. |
| **DHT11 Sensor** | Measures and reads the environmental temperature and humidity conditions. |
| **Breadboard** | Used for prototyping and organizing component connections. |
| **Jumper Wires** | Connects the components together. |
| **USB Cable** | Used to connect the NodeMCU to the PC for programming and power. |


---

## Working and Functionality

The NodeMCU and DHT11 sensor form the core of the system.

1.  **Sensing:** The **DHT11 sensor** reads the current temperature and humidity from the environment.
2.  **Processing:** The **NodeMCU** receives this data, processes it, and transmits it over Wi-Fi.
3.  **Cloud Integration:** The data is transmitted to the **ThingSpeak cloud platform**.
4.  **Monitoring:** The data is updated every **5-15 seconds**, allowing users to monitor climate conditions remotely.
5.  **Visualization:** ThingSpeak then visualizes the readings in graphs, making it easy to analyze trends over time.

---

## Project Image

![IMG_20250302_000607](https://github.com/user-attachments/assets/ae64ad83-9bae-4406-bff2-98076cae1525)
