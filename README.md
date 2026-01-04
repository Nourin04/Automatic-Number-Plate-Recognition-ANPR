# Automatic-Number-Plate-Recognition-ANPR


## Project Description

This project focuses on building an **Automatic License Plate Detection and Recognition (ALPR)** system using classical computer vision techniques and Optical Character Recognition (OCR). The system takes a vehicle image as input, detects the license plate region, extracts it, recognizes the characters on the plate, and displays the result on the original image.

The solution is lightweight, does not require training any machine learning model, and runs efficiently on a CPU. It is suitable for academic projects, proof-of-concept implementations, and beginners in computer vision.

---

## Objectives

* Detect the license plate region from a vehicle image
* Isolate the detected license plate using image processing techniques
* Recognize alphanumeric characters on the license plate
* Display the detected license number on the original image

---

## System Architecture Overview

The system follows a sequential pipeline:

1. Image acquisition
2. Image preprocessing
3. Edge detection and contour extraction
4. License plate localization
5. License plate cropping
6. Optical Character Recognition
7. Result visualization

Each stage improves the accuracy and reliability of the final recognition output.

---

## Output
<img width="1213" height="584" alt="image" src="https://github.com/user-attachments/assets/8656246f-6d22-4d5d-97f3-6db328089e99" />
<img width="1205" height="587" alt="image" src="https://github.com/user-attachments/assets/1270a014-989c-44fd-990c-726086a02e65" />


---

## Tools and Technologies Used

* Python
* OpenCV for image processing
* EasyOCR for text recognition
* NumPy for numerical operations
* Matplotlib for visualization

---

## Applications

* Traffic monitoring systems
* Parking management solutions
* Toll booth automation
* Vehicle identification systems
* Smart city surveillance

---

## Limitations

* Performance depends on image quality and lighting conditions
* Struggles with highly skewed, blurred, or damaged license plates
* OCR accuracy may vary for non-standard fonts or styles

---

## Future Enhancements

* Support for video and real-time license plate detection
* Integration with deep learning–based detection models
* Improved accuracy under low-light conditions
* Multi-language and regional license plate support
* Database integration for vehicle tracking

---



