# blind-indoor-object-detection
This project uses the YOLO (You Only Look Once) object detection model to identify objects in an image and generate an audio summary of the detected objects by TTS.

# YOLOv8 Indoor Object Detection

This project implements an indoor object detection system using the YOLOv8 model. It trains on a Kaggle dataset of indoor objects and performs inference on uploaded images.

## Requirements

- `ultralytics`
- `kaggle`
- `gTTS`
- `tqdm`

Install the required libraries:

```bash
pip install ultralytics kaggle gTTS tqdm

Usage
After uploading an image, the model will detect objects and display bounding boxes.
A summary of detected objects will be read aloud using text-to-speech.
Dataset
This project uses the Indoor Object Detection dataset from Kaggle.
