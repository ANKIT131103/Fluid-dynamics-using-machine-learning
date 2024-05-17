# Fluid-dynamics-using-machine-learning
# Video Frame Extractor

This Python script extracts frames from a video file at regular intervals and saves them as individual image files. It utilizes OpenCV library for video processing.

## Prerequisites

- Python 3.x
- OpenCV (cv2) library

## Installation

1. Clone this repository to your local machine:


2. Install OpenCV library if not already installed:


## Usage

1. Place the video file you want to extract frames from in the same directory as the script, or specify the path to the video file in the `input_video_path` variable.

2. Set the output directory where you want to save the extracted frames by modifying the `output_frames_dir` variable.

3. Run the script:


## Functionality

The `extract_frames` function reads the input video file frame by frame. It extracts every fifth frame and saves it as a JPEG image in the specified output directory. You can adjust the frame extraction interval by modifying the condition `frame_count % 5 == 0` in the code.

##  we caluculate the energy  of fluid of top 10 modes and then adding noise to it and follow the same steps again .
