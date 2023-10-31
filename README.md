# IMUCalibrationUI
The code is written in MATLAB and displays the live BNO055 IMU orientation.

Open "IMU_data_logger_UI.mlapp" in Matlab.

BNO055 should be connected to Arduino or any other microcontroller that can output the BNO055 quaternion notation to the serial port.
It is hardcoded in the program the Arduino board is connected to "COM9" and bandwidth "115200". This may be different in your case. Change the code accordingly on line 81 in "IMU_data_logger_UI.mlapp"

Once, the changes are completed, you are ready to execute the code.
For notes regarding Calibration and Notation, refer to 'Calibration and Notation.txt'

The app has the following functionalities:
- You can start and stop the data logging
- IMU calibration status indicator
- Live view of the BNO055 rotations
- Quaternion and Euler angles output

! Warnings:
- Ignore the Manual Entry text field
- Ignore the Go button
- Ignore the Record Data button
They are for the future development of the app.

