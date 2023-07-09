# Face Age and Gender Estimation

This project uses OpenCV to perform face detection and estimate the age and gender of the detected faces in a video feed from a webcam.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV
- Numpy

## Usage

1. Clone the repository:

   ```shell
   git clone https://github.com/Srish0218/face-age-gender-estimation.git
2. Navigate to the project directory:

   ```shell
   cd face-age-gender-estimation
3. Run the script:

   ```shell
   python age_gender_estimation.py
4. The script will open a window displaying the video feed from your webcam. It will detect faces in each frame and overlay the predicted age and gender on the faces.

5. Press the 'q' key to quit the script and close the window.

##Customization
You can modify the script to suit your needs:

Adjust the confidence threshold for face detection by changing the value in the if confidence > 0.7 condition.
Customize the labels for age and gender by modifying the ageList and genderList arrays.
Experiment with different pre-trained models for face detection, age estimation, and gender classification.

##Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

##Acknowledgments
The face detection, age estimation, and gender classification models used in this project are based on the following research papers:

Face detection: "One Millisecond Face Alignment with an Ensemble of Regression Trees" by Vahid Kazemi and Josephine Sullivan.
Age estimation: "Age and Gender Classification using Convolutional Neural Networks" by Gil Levi and Tal Hassner.
Gender classification: "Gender Classification using Convolutional Neural Networks" by Gil Levi and Tal Hassner.
sql

