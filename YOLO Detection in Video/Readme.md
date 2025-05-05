# YOLO Object Detection on Videos

This project demonstrates how to detect animals and objects in a video using YOLOv5 and save the detected video.

## Requirements

- Python 3
- PyTorch
- OpenCV
- Google Colab (Optional, but this example uses it)

## Files

- `Elephant Video.mp4` — Input video containing animals for detection.
- `output_video1.mp4` — Output video with detected objects.

## Setup

1. **Mount Google Drive** (if using Colab) and upload your video (`Elephant Video.mp4`).
2. **Install Required Libraries** (Torch, OpenCV). On Colab, these are mostly pre-installed.

## Notes

- This code uses the YOLOv5s model from Ultralytics repository to detect animals and objects.
- Detected objects are labeled with bounding boxes and class names.
- Processed video is saved as `output_video1.mp4` in your Google Drive.
- Detection thresholds (confidence and IoU) can be adjusted.
- Uses OpenCV for drawing and saving the video, and Google Colab display functions for output.

