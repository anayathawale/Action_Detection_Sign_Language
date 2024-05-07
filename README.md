# Action Detection Project

## Description
This project utilizes TensorFlow, OpenCV, and MediaPipe to detect and classify human actions from video input using a Long Short-Term Memory (LSTM) neural network. The model interprets pose estimations to recognize actions like 'hello', 'thanks', and 'I love you' in real-time.

## Features
- Real-time action recognition from video feeds.
- Keypoint extraction from human figures using MediaPipe.
- Action classification using an LSTM network.
- Visual feedback of detected actions and confidence levels.

## Installation
Install the required packages via pip:
'''bash
    pip install tensorflow opencv-python-headless mediapipe matplotlib numpy
'''


## Usage
Run the Jupyter notebook `action_detection.ipynb` to start the action detection system. The notebook guides you through the process of capturing video, processing it to detect actions, and displaying the results.

## Code Structure
- **Keypoint Detection:** Extract keypoints using MediaPipe.
- **Data Preparation:** Organize keypoints for model training.
- **Model Training:** Train an LSTM model to recognize actions.
- **Real-time Detection:** Capture video, predict actions, and display results.

## Author
- Anay Athawale

## License
This project is open source and available under the MIT License.

## Acknowledgements
Special thanks to the developers and contributors of TensorFlow, OpenCV, and MediaPipe for making this project possible.

