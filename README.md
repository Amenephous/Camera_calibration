# Camera Calibration Matrix Repository

## Overview
This repository contains code for calibrating a camera using a chessboard pattern. By capturing images of a 7x5 chessboard from various orientations, you can compute the camera's intrinsic parameters and distortion coefficients, essential for correcting distortions in images.

## Prerequisites
To use the camera calibration code, you will need the following:

- **Python**
- **OpenCV**
- **Numpy** 

To install opencv and numpy, you can run the following on the terminal:
```Terminal
  pip install opencv-python
  pip install numpy
```

## Calibration Process
1. **Capture Images**: Obtain a 7x5 chessboard and take pictures of it using the camera you want to calibrate. Ensure that the chessboard is placed in different orientations and positions within the camera's field of view.
 
2. **Organize Images**: Save the captured images in the same directory of this repository. Make sure to include images from various angles and distances.

3. **View Calibration Results**: Once the calibration process is complete, the script will output the camera's intrinsic parameters and distortion coefficients.

## Contributing
Contributions to this project are welcome! If you have any ideas for improvements or bug fixes, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
