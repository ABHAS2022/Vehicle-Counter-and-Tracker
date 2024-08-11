# Traffic Counter and Tracker

This project demonstrates a real-time vehicle detection and counting system using YOLOv8 and OpenCV. The system processes video frames to detect vehicles and maintain a count of the detected vehicles.

## Project Overview

### Features

- **Real-Time Vehicle Detection**: Uses YOLOv8 for detecting vehicles in video frames.
- **Vehicle Counting**: Tracks and counts the number of vehicles in each frame.
- **Output Video**: Generates a video with bounding boxes around detected vehicles and a count displayed on the top of each frame.

### Tools & Technologies

- **YOLOv8**: For vehicle detection.
- **OpenCV**: For video processing and frame manipulation.
- **Python**: The programming language used for implementation.
- **Jupyter Notebook**: For developing and testing the code.

## How to Use

1. **Setup Environment**:
   - Ensure you have the required Python packages installed. If you don't have a `requirements.txt`, you can install the necessary libraries directly:
     ```bash
     pip install ultralytics opencv-python
     ```

2. **Prepare Your Video**:
   - Place your video file in the project directory and rename it to `temp.mp4` or update the filename in the code.

3. **Run the Code in the present .ipynb file at second last cell**:
    - Just change the path of the video file accordingly and see the results saved.
  
4. **Check Results**:
   - After running the script, check the output video file named `output_video_with_count.mp4` for the vehicle detection and counting results.

### Model Performance

- **Validation Accuracy**: 98% (on the validation set)

## Additional Information

- **Github**: [Repository Link](https://github.com/ABHAS2022/Vehicle-Counter-and-Tracker)
- **Date**: March 2023

Feel free to adjust any specific details according to your setup or project requirements.
