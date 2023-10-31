# IMUCalibrationUI
The code is written on MATLAB and displays the live BNO055 IMU orientation.

Open "IMU_data_logger_UI.mlapp" in Matlab.

BNO055 should be connected to arduino or any other micro controller that can output the BNO055 quaternion notation to serial port.
It is hard coded in the program the arduino board is connected to "COM9" and bandwidth "115200". This may be different in your case. Change the code accordingly on line 81 in "IMU_data_logger_UI.mlapp"

Once, the changes are completed, you are ready to execute the code.
For notes regarding Calibration and Noatation, refer to 'Calibration and Notation.txt'

The app has the following functionalities:
- You can start and stop the data logging
- Live view of the BNO055 rotations
- Quaternion and Euler angles output

! Warnings:
- Ignore Manual Entry text field
- Ignore Go button
- Ignore Record Data button
They are for the future development of the app.

