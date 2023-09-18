# TensorTone - Real-time Workout Repetition Counter

TensorTone is an innovative real-time workout repetition counter using computer vision and pose estimation. This project leverages the power of the Mediapipe library and OpenCV to accurately count repetitions for three popular workout exercises: Bicep Curls, High Steppings, and Overhead Shoulder Presses.

## Features

- **Bicep Curl Counter**: TensorTone can count the number of bicep curls performed by analyzing the movement of your arm during the exercise.

- **High Steppings Counter**: It can count the number of high steppings by tracking the movement of your knee during the exercise.

- **Overhead Shoulder Press Counter**: TensorTone can also count overhead shoulder presses by monitoring the motion of your arm and shoulder.

- **Real-time Feedback**: The application provides real-time feedback by displaying the exercise count on the screen as well as the current stage of the exercise (up or down).

## Requirements

- Python 3.x
- OpenCV
- Mediapipe
- NumPy

You can install the required dependencies using the following command:

```bash
pip install opencv-python mediapipe numpy
```

## Usage

1. Clone this repository to your local machine.

2. Open a terminal and navigate to the project directory.

3. Run the Python script for the exercise you want to perform.

4. Follow the on-screen instructions to perform the exercise. The application will count your repetitions in real-time and provide feedback.

## How It Works

TensorTone uses pose estimation to track key landmarks of your body during the exercise. It calculates the angle between specific joints (e.g., shoulder, elbow, wrist) to determine when a repetition is completed. The application also keeps track of the exercise stage (up or down) to ensure accurate counting.


## Acknowledgments

- Thanks to the creators of the Mediapipe library for providing a powerful tool for pose estimation.

- Special thanks to the open-source community for their contributions and support.

## Contact

Thank you for using TensorTone! We hope it helps you in your fitness journey.
