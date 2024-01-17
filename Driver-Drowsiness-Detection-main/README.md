# Driver Drowsiness Detection System

This repository contains the code for a Driver Drowsiness Detection System implemented using Python and various libraries, including OpenCV, TensorFlow, NumPy, Matplotlib, Keras, and Pygame. The goal of this project is to detect when a driver closes their eyes for more than 15 seconds and trigger an alert to prevent potential accidents due to drowsiness.


## Dataset used
http://mrl.cs.vsb.cz/eyedataset


## Features
* Real-time webcam-based drowsiness detection.

* Face detection to identify the driver's face region.

* Eye region extraction from the detected face.

* Eye classification using a pretrained deep learning model.

* Sound alert when drowsiness is detected.

## Installation

1.  Clone the repository to your local machine:
    
```bash
  git clone https://github.com/sakshhhhhhi/Driver-Drowsiness-Detection.git
```

2. Install the required dependencies:

```bash
  pip install opencv-python tensorflow numpy matplotlib keras pygame

```

## Model
The system uses a pretrained deep learning model for eye classification. The model is trained to classify eyes as either open or closed. You can use any suitable architecture for eye classification, such as InceptionV3, ResNet, MobileNetV2, etc. In this sepcific project, it is built by using InceptionV3.


## Contributing

Contributions are welcome! If you find any bugs or want to suggest improvements, please open an issue or submit a pull request.

## Streamlit Integration (Future Plan)

We are actively working on integrating the driver drowsiness detection system with [Streamlit](https://streamlit.io/), a popular Python library that allows us to create web applications for data science and machine learning projects. With Streamlit, we aim to provide a user-friendly interface for accessing and interacting with the drowsiness detection system.

## Disclaimer
This driver drowsiness detection system is for educational and demonstration purposes only. It is not intended to be used in real-world applications without proper testing and validation. The accuracy and reliability of the system may vary based on environmental conditions and hardware. Always prioritize safe driving practices and avoid using any automated systems that may distract the driver. The creators of this project are not responsible for any accidents or damages resulting from the use of this system.
