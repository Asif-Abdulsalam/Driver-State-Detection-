# Driver State Detection

The Driver State Detection project is designed to monitor and analyze the behavior of drivers using 68 Facial Keypoint positions. 

The primary objective of this project is to identify the driver's state while operating a vehicle, particularly during level 2 autonomous driving modes. The model demonstrates robust performance in both daytime and nighttime conditions. 

Utilizing facial keypoints, the system maps various facial features to calculate parameters such as eye lid positions and regions of interest (ROI) around the eyes. Based on these calculations, the model predicts the driver's state, focusing on five distinct states:

**1. Normal State
2. Sleep State
3. Looking Away State
4. Distracted State
5. Tired State**

This project offers a comprehensive approach to enhancing driver safety by detecting and addressing potential hazards arising from various driver states.

To use this project, follow these steps:

1. Download the project files.
2. Navigate to the "Driver state detection master" folder.
3. Open the "Driver state detection" folder.
4. Locate and open the Python file associated with the project.

Before running the project, ensure that you have the necessary libraries installed:

**- OpenCV
- NumPy
- Dlib**

You can install these libraries using a package manager like pip. For example:

```bash
pip install opencv-python numpy dlib
```

Once the libraries are installed, you should be able to run the project successfully. If you encounter any issues, refer to the project documentation or seek assistance from the project contributors.
