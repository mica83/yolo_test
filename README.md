# YOLO Object Detection Demo in Python

## Overview
This repository contains a Python project demonstrating the use of YOLO (You Only Look Once), a state-of-the-art, real-time object detection system. The demo showcases how to implement YOLO with Python to detect objects in images and video streams.

## Prerequisites
Before running the demo, ensure you have the following installed:
- Python 3.6 or later
- OpenCV (cv2)
- YOLOv3 or YOLOv4 weights file
- Corresponding configuration and coco names files

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/mica83/yolo-test.git
   ```
2. Navigate to the cloned directory:
   ```
   cd yolo_test
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
To run the object detection on an image:
```
python yolo_image.py --image path/to/image.jpg
```

For real-time detection on a webcam stream:
```
python main.py --video 0
```

## Features
- Object detection in static images.
- Real-time object detection in video streams.
- Supports YOLOv3 and YOLOv4.

## Customization
- Modify the `yolo_config.py` file to change detection settings, like threshold values, NMS (Non-maximum suppression) threshold, etc.
- Use different weights and cfg files to experiment with other versions of YOLO.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- YOLO (You Only Look Once) by Joseph Redmon and team.
- The OpenCV library.

---
