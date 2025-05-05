# YOLO Object Detection on Images

This project demonstrates how to detect multiple animals and objects in an image using YOLOv5.

## Requirements

- Python 3
- PyTorch
- OpenCV
- Matplotlib
- Google Colab (Optional, but this example uses it)

## Files

- `animals.jpg` — Sample image containing animals for detection.
- `output_image.png` — Output image with detected objects.

## Setup

1. **Mount Google Drive** (if using Colab) and upload your image (`3 animals.jpg`).
2. **Install Required Libraries** (Torch, OpenCV, Matplotlib). On Colab, these are mostly pre-installed.

## Notes

- This code uses the YOLOv5s model from the Ultralytics repository. It can detect many animals like elephants, giraffes, and other objects.
- Confidence threshold and IoU threshold can be adjusted in the code.
- Output is saved as an image (`output_image.png`) with bounding boxes and labels.
- Uses Matplotlib to display results in Colab or Jupyter.

## License

This project is for educational purposes.

