# Gas and Smell Detection System Using Machine Learning

## Overview
This project aims to develop a **gas and smell detection system** using the **BME688 Devkit** and an **ESP32 microcontroller** by applying ADAM optimizer machine learning algorithm on gas resistance data. The system mimics human smell capabilities and can detect various gases, making it ideal for industrial and robotics applications.

## Hardware
- **BME688 Devkit**: Environmental sensor for detecting temperature, pressure, humidity, and gas using AI.
- **Adafruit HUZZAH32 ESP32 Feather**: Handles sensor data, processes it, and sends real-time results via Bluetooth or stores it for later analysis.

## Software
1. **[BME AI-Studio Desktop](https://www.bosch-sensortec.com/software-tools/double-opt-in-forms/bme688-devkit-software-2-3-4-win-form.html)**: A desktop tool for sensor configuration, model training, and analysis.
2. **[BME AI-Studio Mobile App](https://www.bosch-sensortec.com/software-tools/double-opt-in-forms/bme688-devkit-software-2-1-5-form.html)**: For real-time data monitoring and labeling.
3. **[BSEC2 Library](https://github.com/boschsensortec/Bosch-BSEC2-Library)**: Allows custom code development using trained models.
4. **[BME688 Development Kit Software](https://www.bosch-sensortec.com/software-tools/double-opt-in-forms/bme688-devkit-software-2-1-5-form.html)**: Firmware, which needs to be flashed to the ESP32 microcontroller by running the Flash.bat script in the downloaded files from the provided link.

## Methodology
1. **Board Configuration**: Flash firmware, configure sensors. The config used for this project is available in the Src folder.
2. **Sample Collection**: Gather environmental samples using the devkit and mobile app.
3. **Model Training**: Use the BME AI-Studio Desktop to train models on collected data. The project file for the AI-Stdio Desktop are available [here](https://github.com/dhir-g/Gas-and-Smell-Detection/blob/main/Src/Arduino_SP.bmeproject.zip). Please unzip the files and open the project folder from the AI-Studio Desktop application to view my collected specimens and trained algorithms.
4. **Testing**: Evaluate model performance in real-world conditions using the mobile app.

## Results
The system was able to distinguish different smells, such as air, coffee, and tea, achieving 86.66% accuracy. The classification results are depicted in this [video](https://github.com/dhir-g/Gas-and-Smell-Detection/blob/main/Classification%20Results.mp4).

## Future Scope
Potential applications include:
- **Air Quality Monitoring** for smart cities.
- **Health Applications** in wearable devices.
- **Smart Agriculture** and **Home Automation**.
  
For more details, check out the Documentation folder.
