## Driver Drowsiness Detection
## Description
This project focuses on detecting driver drowsiness using computer vision and deep learning techniques. The system analyzes images of the driver's eyes to determine whether they are open or closed, enabling early detection of fatigue and improving road safety for both drivers and passengers.

## Dataset
The dataset used in this project contains 4,000 eye images, divided into two categories:
- Open eyes
- Closed eyes

The dataset is split as follows:
- Training set: 3,400 images
- Testing set: 600 images

==> These images allow the model to learn visual patterns associated with eye closure, which is one of the primary indicators of driver drowsiness.

## Model
A Convolutional Neural Network (CNN) was used to classify eye states into two categories:
- Open

- Closed

CNNs are particularly effective for image classification tasks because they automatically learn spatial features from visual data.

## Technologies & Tools
- Programming Language: Python
- Environment: Google Colab
- Libraries: TensorFlow, Keras, Matplotlib
- Computer Vision: OpenCV (Haar Cascade for face detection)

## Face and Eye Detection
To evaluate the model in a realistic scenario, the system uses the **Haar Cascade algorithm** for face detection.  
This computer vision technique enables the detection of facial features from the webcam feed.

Using the laptop's camera, the system detects the driver's face and focuses on the eye region to determine whether the eyes are open or closed. This allows the model to evaluate driver alertness in real time.

## Evaluation Metrics
The model performance was evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score

These metrics provide a comprehensive evaluation of the model's ability to correctly detect drowsy states.

## Results

### Model Performance (Training)
![Training loss](images/loss-curve.jpg)


![Training Accuracy](images/accuracies-curves.jpg)

### Results Discussion

The obtained results demonstrate the effectiveness of the proposed model in detecting driver drowsiness. The evaluation metrics and learning curves indicate that the model successfully learned meaningful patterns from the training data and achieved reliable performance on unseen data.

These results highlight the robustness of the adopted methodology, as well as the quality of the dataset and the suitability of the chosen model parameters. The learning curves show the progression of the model during training and confirm that the network converges properly without significant overfitting.

Overall, the model shows strong potential for practical applications in driver safety systems, particularly for early detection of fatigue during driving.

### Eye State Classification
The model classifies eye states into two categories: open and closed, which are used as indicators for driver alertness or drowsiness.

## Note
The source code of this project is confidential and is not publicly available. This repository contains only project documentation and example results.



## Author

Wissal Hlioui
Electronis Engineer 

AI Enthusiast