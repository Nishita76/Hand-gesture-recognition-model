# Hand-gesture-recognition
This project demonstrates a hand gesture recognition model using a Convolutional Neural Network (CNN) and a pretrained VGG16 model as the base for feature extraction. The model can accurately identify and classify different hand gestures from image data, enabling intuitive human-computer interaction and gesture-based control systems.

## Dataset
The dataset used in this project is `leapGestRecog`, which consists of images of 10 different hand gestures performed by 10 different subjects. The gestures include:
- Palm (`01_palm`)
- L (`02_l`)
- Fist (`03_fist`)
- Fist Moved (`04_fist_moved`)
- Thumb (`05_thumb`)
- Index (`06_index`)
- OK (`07_ok`)
- Palm Moved (`08_palm_moved`)
- C (`09_c`)
- Down (`10_down`)

## Steps Involved
  The project involves the following steps:
1. **Data Loading and Preprocessing:**  Images are loaded, resized, and normalized.
2. **Data Augmentation:**  Applied to increase the variety of training data.
3. **Model Creation:**  Using VGG16 pretrained model for feature extraction and adding custom dense layers for classification.
4. **Model Training:**  The model is trained on the dataset with a certain number of epochs.
5. **Evaluation:**  The model's performance is evaluated using validation accuracy and loss.
6. **Prediction:**  The model predicts hand gestures for new images.
7. **Visualization:**  The predictions are visualized alongside the input images.

## Result analysis
The final model achieved an impressive '99%' validation accuracy on the test dataset. The model is highly reliable in classifying hand gestures using a Convolutional Neural Network (CNN) and the pretrained VGG16 model and can be confidently used in practical applications like gesture-controlled systems, virtual reality environments, and assistive technologies.
