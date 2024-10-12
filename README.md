# Gas and Smell Detection System Using Machine Learning

## Overview
This project aims to develop a **gas and smell detection system** using the **BME688 Devkit** and an **ESP32 microcontroller** by applying machine learning algorithms on gas resistance data. The system mimics human smell capabilities and can detect various gases, making it ideal for industrial and robotics applications.

## Hardware
- **BME688 Devkit**: Environmental sensor for detecting temperature, pressure, humidity, and gas using AI.
- **Adafruit HUZZAH32 ESP32 Feather**: Handles sensor data, processes it, and sends real-time results via Bluetooth or stores it for later analysis.

## Software
1. **BME AI-Studio Desktop**: A desktop tool for sensor configuration, model training, and analysis.
2. **BME AI-Studio Mobile App**: For real-time data monitoring and labeling.
3. **BSEC2 Library**: Allows custom code development using trained models.

## Methodology
1. **Board Configuration**: Flash firmware, configure sensors.
2. **Sample Collection**: Gather environmental samples using the devkit and mobile app.
3. **Model Training**: Use the BME AI-Studio Desktop to train models on collected data.
4. **Testing**: Evaluate model performance in real-world conditions using the mobile app.

## Results
The system was able to distinguish different smells, such as air, coffee, and tea, achieving 86.66% accuracy.

## Future Scope
Potential applications include:
- **Air Quality Monitoring** for smart cities.
- **Health Applications** in wearable devices.
- **Smart Agriculture** and **Home Automation**.
  
For more details, check out the complete documentation.
