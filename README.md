# Real Time Driver Drowsiness Detection System | OpenCV

## Project Description
The Real Time Driver Drowsiness Detection System utilizes computer vision techniques to monitor driver alertness and detect signs of drowsiness in real-time. This system aims to enhance road safety by providing timely alerts to drivers. The project has been updated to include new features such as improved detection algorithms and user interface enhancements.

## Required Modules
The following Python libraries are essential for the project:
- OpenCV
- NumPy
- PIL (Pillow)
- Matplotlib
- face_recognition
- dlib
- pygame
- logging

## Installation Instructions
To run the Real Time Driver Drowsiness Detection System, you need to install the following dependencies:

1. **Install CMake**:
   ```bash
   pip install cmake
   ```

2. **Install Dlib**:
   Make sure to install the compatible version of Dlib for your Python version:
   ```bash
   pip install dlib-19.24.99-cp312-cp312-win_amd64.whl
   ```

3. **Install Face Recognition**:
   ```bash
   pip install face_recognition
   ```

## Running the Project
1. Open the Jupyter Notebook `drowsiness_detection.ipynb`.
2. Execute the cells sequentially to run the drowsiness detection system. Ensure that the necessary input files are in place.

## Image Input
The system uses an image named `test1.png` for testing. Ensure that this file is present in the project directory. Additional input files may be required for enhanced testing.

## Additional Information
For more details, refer to the [OpenCV documentation](https://opencv.org/documentation/) and [Face Recognition documentation](https://face-recognition.readthedocs.io/en/latest/).

## Troubleshooting
If you encounter any issues, please check the following:
- Ensure all dependencies are installed correctly.
- Verify that the video input file is in the correct format and location.
- Check for common issues related to camera access and permissions.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.
