# YogaVision - Yoga Pose Detection Software

YogaVision is an advanced software application designed to detect yoga poses in real-time using machine learning techniques. With the power of computer vision and machine learning, YogaVision helps users improve their yoga practice by providing instant feedback on the accuracy of their poses.

## Features

- Real-time yoga pose detection using webcam feed.
- Utilizes landmark detection through MediaPipe library for accurate pose estimation.
- Trained machine learning models on the Yoga Poses Dataset available on Kaggle.
- Supported machine learning classifiers: Logistic Regression, Ridge Classifier, Random Forest Classifier, Gradient Boosting Classifier.
- Achieved highest accuracy of 92.69% with Random Forest Classifier.
- Provides feedback on the accuracy of detected yoga poses.

## Installation

1. Clone the repository from GitHub: [YogaVision GitHub Repository](https://github.com/username/YogaVision)
2. Install the required dependencies:
    ```bash
    pip install numpy
    pip install pandas
    pip install pillow
    pip install mediapipe
    pip install scikit-learn
    pip install opencv-python
    ```
3. Download the Yoga Poses Dataset from Kaggle: [Yoga Poses Dataset](https://www.kaggle.com/datasets/niharika41298/yoga-poses-dataset/data)
4. Run the PoseDetection.ipynb file.

## Usage

1. Launch the YogaVision application.
2. Allow access to your webcam.
3. Stand in front of the camera and perform a yoga pose.
4. YogaVision will detect the pose and provide feedback on its accuracy.
5. Adjust your pose according to the feedback provided.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Kaggle user Niharika41298 for providing the Yoga Poses Dataset.
- Google's MediaPipe library for landmark detection.
- Scikit-learn for machine learning classifiers.
- OpenCV for webcam access and image processing.
