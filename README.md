
# Gender and Age Recognition

This project is a real-time gender and age recognition program using deep learning models and OpenCV. It analyzes a video file frame by frame, detects faces, and predicts the gender and age of each detected face.

## Requirements

- Python 3.x
- OpenCV (cv2) library
- Pre-trained models:
  - Face detection: opencv_face_detector.pbtxt and opencv_face_detector_uint8.pb
  - Age prediction: age_deploy.prototxt and age_net.caffemodel
  - Gender prediction: gender_deploy.prototxt and gender_net.caffemodel
- Video file for testing

## Setup and Usage

1. Clone the repository or download the code files.

2. Install the required dependencies using the following command:
   ```
   pip install opencv-python
   ```

3. Place the pre-trained model files in the same directory as the code files.

4. Replace `'4.mp4'` with the path or filename of the video file you want to analyze in the code.

5. Run the code using the following command:
   ```
   python age_gender_recognition.py
   ```

6. The program will open a window titled "Age-Gender" and display the video with bounding boxes around the detected faces and labels for gender and age.

7. To exit the program, press the 'q' key.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The code is based on the OpenCV library and utilizes pre-trained models for face detection, gender prediction, and age estimation. The pre-trained models were obtained from the OpenCV repository and trained on various datasets.

## References

- OpenCV: https://opencv.org/
- OpenCV GitHub Repository: https://github.com/opencv/opencv

Feel free to customize the README file according to your specific needs, including adding more details or instructions specific to your use case.
