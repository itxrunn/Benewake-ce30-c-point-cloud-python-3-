# Example-for-Python3
This is an example to get distance and amplitude data from Benewake CE30-C LiDAR. Feel free to use or modify the code in your projects.

## Files
**dataExchange.py**

  Methods for communication with CE30-C LiDAR.
  
**undistortion.py**

  Methods for calibrate lens distortion.
  
**getCE30CDate.py**

  Example code to get data from CE30-C LiDAR, do undistortion and save undistorted data to a file.
  
## Requirement
  1.Python 3.5 or above
  
  2.Numpy
  
## Run
  ```
  $sudo python getCE30CData.py
  ```
## Credits 

  This code is simalar to that of the original, but this code and its dependencies is upgraded to work with Python 3
  https://github.com/CE30C/Example-for-Python
