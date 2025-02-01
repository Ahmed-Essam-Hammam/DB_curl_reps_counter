# **Pose Detection & Exercise Counter using Mediapipe**  

This project is a **real-time pose detection system** using **Mediapipe Pose and OpenCV**. It detects human body landmarks and calculates joint angles to **track movement and count exercise repetitions**.

---

## **Features**  

✅ **Real-time Pose Detection** using Mediapipe Pose  
✅ **Angle Calculation** for key joints (shoulder, elbow, wrist)  
✅ **Exercise Repetition Counter** using movement tracking  
✅ **Live Video Feed** with annotated pose landmarks  
✅ **Displays Angle & Repetition Count** on screen  

---

## **Installation**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/yourusername/pose-detection.git
cd pose-detection
```

### **2️⃣ Install Dependencies**  
Make sure you have **Python 3.x** installed, then install the required libraries:  
```bash
pip install opencv-python mediapipe numpy
```

---

## **Usage**  

Run the script to start the **Pose Detection & Exercise Counter**:  
```bash
python pose_detection.py
```
- The **webcam will open** and detect **body landmarks**  
- It will calculate angles and count **exercise repetitions**  
- **Press `Esc`** to exit the program  

---

## **How It Works**  

1️⃣ **Initialize Mediapipe Pose**: Loads the **pose detection model**  
2️⃣ **Capture webcam frames**: Reads video input for processing  
3️⃣ **Detect Pose Landmarks**: Identifies key **body points**  
4️⃣ **Calculate Joint Angles**: Computes **shoulder, elbow, and wrist angles**  
5️⃣ **Count Exercise Repetitions**: Detects **up and down movements**  
6️⃣ **Display Count & Angles**: Overlays **live annotations** on video feed  

---

## **File Structure**  

```
📂 pose-detection  
 ├── 📜 pose_detection.py     # Main script for pose detection  
 ├── 📜 README.md             # Project documentation  
```

---

## **Requirements**  

- **Python 3.x**  
- **OpenCV (`cv2`)**  
- **Mediapipe**  
- **NumPy**  

---

## **Notes**  

- **Mediapipe Pose** detects **33 landmarks** of the human body  
- This program **tracks arm movement** and counts **bicep curls**  
- To extend functionality, modify the script for **different exercises**  

---

## **Future Improvements**  

🔹 Support **multiple exercises** (squats, push-ups, etc.)  
🔹 Implement a **GUI** for better usability  
🔹 Save repetition data for **progress tracking**  

---

## **License**  

This project is **open-source** and free to use. Contributions are welcome! 🚀  
