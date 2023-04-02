# Simple Face Emotion Recognition using FER2013 Dataset

This repository contains a simple implementation of face emotion recognition using the FER2013 dataset.

## About the Dataset

The FER2013 dataset contains 35,887 grayscale, 48x48 sized face images with seven emotion labels: angry, disgust, fear, happy, neutral, sad, and surprise. The dataset can be found on [Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data).

## About the Implementation

The implementation uses deep learning techniques to recognize facial emotions. We use a convolutional neural network (CNN) to learn features from the images, and a fully connected layer to predict the emotion labels.

### Dependencies

- Python 3.6 or later
- TensorFlow 2.x
- OpenCV 2.x

### Running the Code

1. Clone this repository:

```
git clone https://github.com/farroshsy/Simple-EmotionRecognition.git
```

2. Install the dependencies:

```
pip install tensorflow opencv-python
```

3. Download and extract the FER2013 dataset from [Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) to a directory named `datasets`.
4. Run the demo on a video file:

```
python3 video_emotion_color_demo.py
```

The demo will display the emotions of people in the video as color-coded rectangles around their faces.

### Photo Example
<img width="1276" alt="image" src="https://user-images.githubusercontent.com/86004023/229332079-7b4a993a-508c-4dc1-a2eb-4c315360619b.png">




