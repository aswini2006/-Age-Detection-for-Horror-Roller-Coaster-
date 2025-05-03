# Age & Gender Detection for Ride Access Control

## Overview
This project uses deep learning models to predict the age and gender of individuals from video frames. Based on predefined age criteria, it determines whether a person is allowed on the ride.

## Features
- Uses **OpenCV** for video frame processing.
- **Keras** deep learning models for age and gender prediction.
- **Pandas** to log and store predictions in a CSV file.
- Operates on a sample video uploaded to **Kaggle** datasets.

## How It Works
- Load pre-trained deep learning models from Kaggle.
- Process each frame of the video and extract facial features.
- Predict age and gender using the models.
- Determine ride access eligibility (Allowed/Not Allowed).
- Log the results and save them as a CSV file.
  
## Usage
Upload your video to Kaggle and modify video_path in the script to reflect its location. Then, run:
python age_gender_detection.py

## License
This project is licensed under the MIT License. Feel free to use and modify it!

