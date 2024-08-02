# Face Recognition Attendance System

This project is a Face Recognition Attendance System that uses the `face_recognition` library to detect and recognize faces from a video feed, and marks attendance by recording the time each recognized person appears.

## Summary

The code accomplishes the following tasks:
1. **Image Loading and Encoding**: Loads images from the `projectimages` directory, processes them to extract facial features (encodings), and stores these encodings for later comparison.
2. **Face Recognition in Real-Time**: Captures video from a webcam, detects faces in the live feed, and compares them with the stored encodings to recognize known individuals.
3. **Attendance Marking**: Records the attendance of recognized individuals by logging their name and the current time in `attendance.csv`.

## Features

- **Face Encoding**: Encodes faces from images in a specified folder.
- **Face Recognition**: Recognizes faces from a live webcam feed.
- **Attendance Marking**: Records the attendance of recognized faces with the current time.

## Requirements

- Python 3.x
- OpenCV
- face_recognition
- numpy
