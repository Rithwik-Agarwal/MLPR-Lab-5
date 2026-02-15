# Lab 5: Machine Learning and Pattern Recognition (Spring 2026)

## 📌 Overview
This repository contains the submission for **Lab 5**, focused on Computer Vision and Machine Learning concepts. The primary objective of this lab was to implement object detection techniques using **Haar Cascades**.

## 🎯 Aim
* To implement and demonstrate **Face Detection** on a group image using OpenCV's pre-trained Haar Cascade classifiers.

## 🛠️ Methodology

### Face Detection
* **Library Used:** `OpenCV` (`cv2`).
* **Technique:** Haar Feature-based Cascade Classifiers.
* **Process:**
    1.  **Image Loading:** Loaded the target image (`plaksha_Faculty.jpg`).
    2.  **Preprocessing:** Converted the image from BGR to Grayscale (`cv2.cvtColor`) to improve computational efficiency and detection accuracy.
    3.  **Detection:** Applied `face_cascade.detectMultiScale()` with tuned parameters (`scaleFactor=1.05`, `minNeighbors=4`) to identify faces.
    4.  **Visualization:** Drew bounding boxes around detected faces and labeled them using `cv2.rectangle` and `cv2.putText`.

## 📊 Key Findings

### Face Detection Results
* The Haar Cascade model successfully detected multiple faces in the provided faculty image.
* Total Faces Detected: 30


## 🖼️ Visualisations
<img width="1274" height="853" alt="image" src="https://github.com/user-attachments/assets/d298ff5d-d4a6-49c8-9412-dadbd4387edc" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/e79723c3-7fe7-4c9f-9091-fa22741da98a" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/f9d22a16-d33d-49e7-829c-59a7ebb8df13" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/ac902bb8-68db-4688-95a8-38aa78915344" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/adeb8e5b-ac28-43b3-9bb0-75f2498a917f" />

## 📂 Files Included
* `Lab 5 Spring 2026.ipynb`: The Jupyter Notebook containing the code and report answers.
* `plaksha_Faculty.jpg`: The input image used for face detection.
* `Dr_Shashi_Tharoor.jpg`: New image.
* `README.md`: Project documentation.

## 💻 Dependencies
To run this notebook, ensure you have the following libraries installed:
```bash
pip install opencv-python numpy matplotlib scikit-learn scipy
