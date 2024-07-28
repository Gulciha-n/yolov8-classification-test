# YOLOv8 Ultralytics Classification Test with PyTorch

This repository contains a script for testing image classification using a YOLOv8 model. The script performs classification on a given image, saves the results to text files, and annotates the image with classification labels and confidence scores.

## Features

- **YOLOv8 Model**: Utilizes a pretrained YOLOv8 classification model for image classification tasks.
- **Classification Results**: Saves classification results to text files with labels and confidence scores.
- **Image Annotation**: Annotates images with classification labels and confidence scores, and saves them.

## Installation

To run this script, you'll need to have the following dependencies installed:

- [Python 3](https://www.python.org/downloads/)
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) (Install via `pip install ultralytics`)
- [OpenCV](https://opencv.org/) (Install via `pip install opencv-python`)
- [Pathlib](https://docs.python.org/3/library/pathlib.html) (Included in Python 3.4+)

You can install the required Python packages using:

```bash
pip install ultralytics opencv-python
```

## Usage

1. **Set Model Path:**
   - Update the `MODEL_PATH` variable with the path to your pretrained YOLOv8 model.

2. **Set Image Path:**
   - Update the `SOURCE` variable with the path to the image you want to test.

3. **Run the Script:**
   - Execute the script to perform image classification.

4. **Results:**
   - Classification results will be saved in text files in the `results` directory.
   - Annotated images will also be saved in the same directory.

## Repository

- **Download the repository:** https://github.com/Gulciha-n/yolov8-ultralytics-classification-test


## Contributing

We welcome contributions to this project! If you have suggestions, improvements, or bug fixes, please submit an issue or a pull request on GitHub. Your feedback and contributions are greatly appreciated.
