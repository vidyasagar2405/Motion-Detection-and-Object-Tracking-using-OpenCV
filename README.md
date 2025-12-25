# Motion-Detection-and-Object-Tracking-using-OpenCV

This project demonstrates real-time **motion detection and object tracking** using **frame differencing**, **thresholding**, and **contour-based detection** in OpenCV.

---

## 🧠 Overview

The system captures frames from a webcam or a video file and compares consecutive frames to detect movement. It identifies all moving objects, outlines them with **rotated bounding boxes**, and visualizes their **motion boundaries**.

This technique can be used for:

* Security camera motion alerts
* Human or vehicle tracking
* Surveillance system prototypes
* Automated video analysis

---

## 🚀 Features

* Frame differencing for motion detection
* Gaussian blur for noise reduction
* Thresholding for clear motion segmentation
* Contour detection and bounding box drawing
* Works on both webcam feeds and video files
* Adjustable threshold values for fine-tuning

---

## 🧩 Tech Stack

* **Python 3.x**
* **OpenCV (cv2)**
* **NumPy**

---

## 🧰 Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/vidyasagar2405/motion-detection-and-object-tracking.git
   cd motion-detection-and-object-tracking
   ```

2. Install dependencies:

   ```bash
   pip install opencv-python numpy
   ```

---

## 🎯 How It Works

1. Reads two consecutive frames from video input.
2. Calculates their **absolute difference** to detect motion.
3. Converts the difference to grayscale and applies **Gaussian blur**.
4. Uses **binary thresholding** and **contour detection**.
5. Draws bounding boxes around all moving objects.

---

## Demo Video
## [Video](https://youtu.be/0tb8nrONalw)

## 🖼️ Sample Output

---

* Green contours: Detected motion regions
* Red boxes: Tracked moving objects
* Blue dots: Object centers (optional)

---

## 🧩 Future Enhancements

* Add motion tracking across multiple frames
* Integrate object classification (e.g., human vs vehicle)
* Display real-time motion area percentage
