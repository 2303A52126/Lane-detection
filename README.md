# Lane-detection
Lane detection system using OpenCV
# Lane Detection System using OpenCV

## 📌 Project Overview
This project implements a lane detection system using OpenCV that processes road video footage **frame by frame** to detect and track **left and right lane boundaries**.  
The system focuses on identifying outer lane markings and overlaying them on the video to simulate a basic lane detection pipeline used in driver-assistance systems.

---

## 🚀 Features
- Detects **left and right lane boundaries**
- Processes video **frame by frame**
- Uses **Canny Edge Detection** for edge extraction
- Applies **Region of Interest (ROI) masking** to focus on the road area
- Uses **Hough Line Transform** for lane detection
- Filters noise using slope and position constraints
- Produces **stable lane overlays** across consecutive frames

---

## 🛠 Technologies Used
- Python
- OpenCV
- NumPy

---

## 📂 Project Structure

---

## ▶️ How to Run the Project
1. Clone the repository:

2. Install dependencies:

3. Run the script:

4. The output video with detected lane boundaries will be generated.

---

## 📌 Output
The system generates a processed video where the detected left and right lane boundaries are highlighted on the original road footage.

---

## 🔮 Future Improvements
- Vehicle position (lane offset) estimation
- Curved lane detection
- Lane departure warning system
- Deep learning-based lane detection

---

## 🏁 Conclusion
This project demonstrates the application of **classical computer vision techniques** to solve a real-world problem and serves as a strong foundation for learning autonomous driving concepts.
