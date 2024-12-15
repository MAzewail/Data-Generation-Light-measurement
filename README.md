##  Alternative Approach with LDR Sensor (README Update)

This repository also includes an alternative approach for data collection using an LDR sensor (Light Dependent Resistor). This method allows for training a regression model based on actual light intensity measurements instead of relying solely on camera data and pre-defined levels.

**New Script: ldr_data_acquisition.py**

The script `ldr_data_acquisition.py` utilizes an LDR sensor to capture light intensity readings and capture corresponding images.

**Modifications to README.md:**

1. **Project Description:**
    - Add a paragraph describing the alternative approach using an LDR sensor.
    - Briefly explain how the LDR sensor interacts with the script and Arduino.

2. **Features:**
    - Update the features list to include:
        - LDR sensor integration for light intensity measurement.
        - Data collection for regression model training.

3. **Setup Instructions:**
    - Add a new step for connecting the LDR sensor to the Arduino board.
    - Briefly mention any modifications needed in the Arduino program to send light intensity readings.

4. **How to Use:**
    - Specify which script to run for LDR data collection (`python ldr_data_acquisition.py`).
    - Describe the generated output:
        - Images with filenames including the measured light intensity.
        - A CSV file (`labels.csv`) containing image names and corresponding light intensity values.

5. **Additional Notes:**
    - Mention the script captures light intensity readings from the LDR sensor.
    - Suggest additional libraries like NumPy for further data analysis.


**Here's an example of the updated section for the LDR approach:**

###  Alternative Approach with LDR Sensor

This project offers an alternative approach for data collection using an LDR sensor. This method allows us to capture actual light intensity measurements and train a regression model for more precise light intensity estimation. The LDR sensor is connected to the Arduino board, which transmits the measured light intensity values to the script via serial communication.

**Additional Notes:**

* The script `ldr_data_acquisition.py` utilizes an LDR sensor to capture light intensity readings and capture corresponding images.
* Ensure your Arduino program is configured to send light intensity readings received from the LDR sensor.
* Consider using libraries like NumPy for advanced data analysis after capturing light intensity values and images.
