# Animal Movement Tracking using Graph Theory

This project demonstrates how to track and visualize animal movement paths as a graph using Python libraries like OpenCV and NetworkX.

## Requirements

- Python 3  
- OpenCV  
- NumPy  
- NetworkX  
- Matplotlib  
- Google Colab (Optional, but this example uses it)

## Files

- `animal_movement_tracking.mp4` —  containing the tracking and graph visualization code.
- `Zebra1.mp4` — Sample wildlife video for testing (optional).
- `graph.png` — Example output showing movement paths.

## Setup

1. **Upload Files**:
   - Upload your sample video (e.g., `Zebra1.mp4`) to your Google Drive 

2. **Install Dependencies**:
   - On Google Colab, you can install any missing libraries using:
     ```python
     !pip install networkx matplotlib
     ```

## Notes

- Each detected animal movement is represented as a node. Their paths are shown as edges connecting these nodes.
- You can extend this analysis by applying graph algorithms (e.g., centrality, clustering) to study movement patterns.
- If using Google Colab, use `cv2_imshow()` to display images instead of `cv2.imshow()`.

