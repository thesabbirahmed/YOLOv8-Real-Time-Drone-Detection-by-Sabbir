# Real-Time-Drone-Detection-System

This project demonstrates real-time drone detection using YOLOv8 based on YOLOv5 and OpenCV for more easier and faster detection. It detects drones in real-time and displays a warning when a drone is detected inside or near a defined rectangle.


## Features

- Real-time drone detection using YOLOv8 based on YOLOv5 framework
- Interactive rectangle creation and adjustment
- Warning message displayed when a drone is detected inside or near the rectangle



## Benefits
1. Live Feedback
Immediate alerting and notifications offer prompt reactions to potential drone risks.

2. Automated Surveillance
Minimize human monitoring with the automation of drone identification through computer vision and machine learning techniques.

3. Adaptable and User-Friendly
Set and modify the detection zone with an intuitive rectangular tool for precise and flexible identification.

4. Elevated Safety Measures
Immediate drone identification for bolstered security at airports, public gatherings, and limited-access zones.


## About the Dataset (Roboflow)

The Drone Detection model utilized a comprehensive dataset with 1400 images showcasing various drone types. This dataset was meticulously assembled and annotated to guarantee precision in the labels. It encompasses an extensive variety of drone sizes, styles, angles, and environments.

The dataset was crafted using the "Roboflow Platform" and was retrieved via its API. This approach simplified the data preparation phase and guaranteed top-notch inputs for model training.

Having access to such a varied and meticulously labeled dataset allows the Drone Detection model to be trained on a broad spectrum of drone images, leading to enhanced precision and dependability in real-world detection situations.

## Requirements

- Python 3.x
- OpenCV
- PyTorch
- YOLOv5
- Numpy
- PIL

## Installation

1. Clone the repository:

   - git clone https://github.com/thesabbirahmed/YOLOv8-Real-Time-Drone-Detection-by-Sabbir

2. Install the required Python libraries:

   - pip install opencv-python torch numpy pillow

3. USe the YOLOv8 model based on YOLOv5 framework:

   - YOLOv8 is built on the YOLOv5 framework and includes several architectural and developer experience improvements. YOLOv8 based on YOLOv5 is easier to use, faster and more accurate. 

## Usage

1. Run the `Advanced_Drone_Detection.py` script:
   - python Advanced_Drone_Detection.py

2. The program initiates a real-time video stream using the primary camera.
   - Press and drag the mouse across the video feed to outline the rectangle's boundaries.
   - You can modify the rectangle by pulling its corners.
   - An alert will pop up when a drone is spotted within or close to the rectangle.

3. Press 'q' to quit the program.
