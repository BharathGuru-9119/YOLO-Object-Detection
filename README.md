# YOLO Object Detection 

## Overview

This project demonstrates **object detection** using the YOLO (You Only Look Once) algorithm with OpenCV and Python.  
It processes images and videos, highlighting detected objects such as dogs, cars, people, and more.  
The repository includes sample code for both real-time webcam detection and video file analysis.

## Features

- **YOLOv4 & YOLOv5 Integration**: Supports both models for object detection.
- **Image and Video Processing**: Detect objects in photos and videos.
- **Real-Time Detection**: Capture from webcam and visualize detected objects live.
- **Class Labels**: Uses standard COCO dataset labels (e.g., dog, car, person).
- **Bounding Boxes**: Annotates detected objects with bounding boxes and confidence scores.

## Example Output

### Image Output

- Detected object: Dog  
  The system has drawn a bounding box around a dog in the grass.

![Sample Output: Dog Detection](<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/9f6219e2-843d-4718-ab3e-06fc82735a66" />
)


### Video Output

- Detected objects in each frame (dog, person, car, etc.):
  - Bounding boxes and labels are rendered frame-by-frame.
  - Video is saved with annotations as `output1.mp4`.

## Getting Started

1. **Clone the Repository**
   ```
   git clone https://github.com/your-username/yolo-object-detection-demo.git
   ```
2. **Install Dependencies**
   ```
   pip install opencv-python numpy
   ```
   For YOLOv5 (PyTorch):
   ```
   pip install torch torchvision
   ```

3. **Download YOLO Model Files**
   - For YOLOv4: `yolov4.cfg`, `yolov4.weights`, `coco.names`
   - For YOLOv5: Use `torch.hub` to automatically download weights.

4. **Run Example Notebooks**
   - `abc.ipynb`, `Untitled1.ipynb`, `Untitled2.ipynb`

## Usage

- **Webcam Detection**  
  Run the notebook or script. Press 'q' to exit.
- **Video Detection**  
  Specify the video file path in the script to process and annotate frames.

## Files

- `abc.ipynb`: YOLOv5 real-time webcam object detection (Python, OpenCV, PyTorch).
- `Untitled1.ipynb`: YOLOv4 real-time webcam detection (Python, OpenCV).
- `Untitled2.ipynb`: YOLOv4 video file detection and annotated video output.
- `yolov4.cfg`, `yolov4.weights`, `coco.names`: Model configuration, weights, and class labels.
- `labels.txt`, `labels (2).txt`: Additional class label files.

## Sample Classes

- person, bicycle, car, motorbike, dog, cat, horse, etc.

## Contributing

Feel free to submit issues or pull requests for improvements—such as adding new detection classes, improving annotation, or supporting additional models.

## License

For research and educational purposes only.

---
