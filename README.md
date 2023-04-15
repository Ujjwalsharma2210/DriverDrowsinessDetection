# Drowsiness Detection using Haar Cascade Algorithm

This program uses the Haar Cascade Algorithm to detect the drowsiness of a person. It tracks the eyes of the person and checks if they are closed for a certain period of time, which is an indication of drowsiness.

## Requirements

- Python 3.x
- OpenCV 4.x
- NumPy
- Pygame

## Installation

Clone the repository:

```bash
git clone https://github.com/Ujjwalsharma2210/DriverDrowsinessDetection.git
```

Install the required packages:

```bash
pip install opencv-python numpy
```

## Usage

1. Navigate to the project directory:

```bash
cd "folder-name"
```

2. Run the program:

```bash
python drowsiness_detection.py
```

3. The program will open your default camera and start detecting your eyes. If your eyes are closed for more than a certain duration, an alarm will be raised to alert you.

## Credits

The Haar Cascade Algorithm implementation is based on this tutorial.<br>
[Eye blink detection with openCV, python and dlib](https://pyimagesearch.com/2017/04/24/eye-blink-detection-opencv-python-dlib/)<br>
[Drowsiness detection with openCV](https://pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)
