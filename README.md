# Real-Time Face Recognition using FisherFace and Haar Cascade

A machine learning-based face recognition system developed using Python and OpenCV. The project uses a custom facial image dataset to train a FisherFace recognizer and performs real-time face recognition through a webcam. The FisherFace recognizer was trained by myself using different datasets.

## Features

- Real-time face detection using Haar Cascade
- Custom dataset creation
- FisherFace model training
- Live face recognition
- Unknown face detection using confidence thresholding

## Technologies

- Python
- OpenCV
- Haar Cascade
- FisherFace Recognizer

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
python dataset_collection.py
python face_recognition.py
```

## Future Improvements

- Integrate deep learning-based face recognition (FaceNet/ArcFace)
- Improve recognition under varying lighting conditions
- Save and load trained models instead of retraining every run
