# Aquasens
AQUASENS is an IoT based device which is capable of monitoring multiple water parameters like pH, TDS, temperature, DO (currently these parameters only, more will be added in future) and display all these data on the mobile/laptop anywhere in the world with the help of internet. 
# Core Concept
AQUASENS is a smart water quality monitoring system designed for aquariums and aquaponics setups that allows remote monitoring and control of critical water parameters from anywhere in the world.
# Technical Architecture
Hardware Design (Dual-Brain System):

1. Primary Brain (Arduino Mega): Collects data from multiple sensors and processes readings
2. Secondary Brain (D1 Mini/ESP8266): Handles WiFi connectivity and cloud communication
3. Sensors Suite: pH, TDS (Total Dissolved Solids), Temperature (DS18B20), Dissolved Oxygen
4. Control System: 4-channel relay module for controlling heating rods, pumps, filters, and air pumps

# Data Flow
Sensors → Arduino Mega → Serial Communication (9600 baud) → D1 Mini → WiFi → Blynk IoT Cloud → Mobile/Web App

# Key Features
Current Capabilities:

1. Real-time monitoring of 4 water parameters
2. Remote access from anywhere via internet
3. Bidirectional control (send commands to control aquarium equipment)
4. Local OLED display for at-a-glance readings
5. Synchronized across devices (phone, laptop, etc.)

Planned Future Innovations:

1. Pre-loaded databases for plant and fish requirements
2. Predictive analytics for ammonia, nitrate, nitrites
3. OpenCV integration for visual plant health monitoring
4. Automated treatment systems for fish and plant illnesses
5. Bio-filter waste extraction for fertilizer production
6. Breeding optimization with specialized parameters for fry and eggs
