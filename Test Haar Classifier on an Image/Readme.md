# Elephant Detection using Haar Cascade Classifier

This demonstrates how to detect elephants in an image using a Haar cascade classifier trained specifically for elephants.

## Requirements

- Python 3
- OpenCV
- Google Colab (Optional, but this example uses it)

## Files

- `cascade.xml` — Pre-trained Haar cascade classifier for elephant detection.
- `pexels-photo-4577141.jpeg` — Sample image for testing.
- `elephant_detection.ipynb` — Colab notebook containing the detection code.

## Setup

1. **Upload Files**:
   - Upload your `cascade.xml` and sample image (e.g., `elephant.png`) to your Google Drive.
   - mount your drive

2. **Install Dependencies**:
   - Make sure OpenCV is installed. If using Colab, it's pre-installed.

## Notes

- This classifier is specifically trained for elephant detection. Results may vary depending on the quality and angle of the image.
- If you're using Google Colab, use `cv2_imshow()` for displaying images instead of `cv2.imshow()`.



