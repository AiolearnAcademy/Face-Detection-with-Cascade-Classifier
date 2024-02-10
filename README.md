# Face-Detection-with-Cascade-Classifier

```
# Face Detection with Cascade Classifier

This project demonstrates face detection using the OpenCV Cascade Classifier. The script loads an image, converts it to RGB format, and applies the pre-trained Cascade Classifier model to detect faces in the image. The detected faces are then highlighted with green rectangles.

# Usage

To use this script, you will need to have OpenCV installed on your system. You can install OpenCV using pip:

```
pip install opencv-python
```

Once OpenCV is installed, you can run the script by executing the following command:

```
python face_detection.py
```

This will load the image "nima.jpg" from the current directory and display the detected faces in a matplotlib window.

## Model

The script uses a pre-trained Cascade Classifier model to detect faces. The model is based on the Haar-like features algorithm and is trained on a large dataset of human faces. The model is included in the repository as the file "model.xml".

## Output

The output of the script is an image with the detected faces highlighted with green rectangles. The image is displayed in a matplotlib window.

## Limitations

The Cascade Classifier model is not perfect and may not be able to detect all faces in an image. The accuracy of the model depends on the quality of the image and the lighting conditions.

## Conclusion

This script provides a simple example of how to use the OpenCV Cascade Classifier to detect faces in an image. The script can be used as a starting point for developing more complex face detection applications.
```
