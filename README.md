# Hand Gesture Recognition System

## Overview
This project implements a real-time hand gesture recognition system using computer vision and machine learning techniques. The system can recognize various hand gestures and can be used for applications like sign language interpretation, human-computer interaction, and virtual reality control.

## Features
- Real-time hand gesture recognition
- Support for multiple hand gestures
- High accuracy prediction
- Easy-to-use interface
- Real-time visualization of predictions

## Prerequisites
- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- scikit-learn
- Other dependencies listed in requirements.txt

## Installation
1. Clone this repository
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Project Structure
```
├── data_new/           # Dataset directory
├── kaggle/            # Kaggle dataset files
├── hand_sign_recognisition.ipynb  # Main implementation notebook
├── model.p            # Trained model file
├── data.pickle        # Processed data file
├── pre.jpg           # Pre-processing example
├── post.jpg          # Post-processing example
└── requirements.txt   # Project dependencies
```

## Usage
1. Run the Jupyter notebook `hand_sign_recognisition.ipynb`
2. The notebook contains the complete implementation including:
   - Data preprocessing
   - Model training
   - Real-time prediction
   - Visualization

## Implementation Details
The system uses the following key components:
1. **Hand Detection**: Using MediaPipe for hand landmark detection
2. **Feature Extraction**: Extracting key points from hand landmarks
3. **Model Training**: Using scikit-learn for gesture classification
4. **Real-time Prediction**: Processing webcam feed for live gesture recognition

## Dataset and Examples
The project includes a comprehensive dataset of hand gestures. Here are some examples:

### Dataset Samples
![Dataset Samples](dataset_samples.png)

### Example Gesture
![Example Gesture](1.png)

## Results
The system achieves high accuracy in recognizing various hand gestures. The implementation includes:
- Pre-processing of hand images
- Feature extraction from hand landmarks
- Real-time prediction and visualization

### Preprocessing Example
![Preprocessing Example](2.png)

## Future Improvements
- Add support for more hand gestures
- Improve real-time performance
- Add support for multiple hands
- Implement gesture sequence recognition

## License
This project is open source and available under the MIT License.

## Acknowledgments
- MediaPipe for hand landmark detection
- scikit-learn for machine learning implementation
- OpenCV for computer vision tasks 