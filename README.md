# Vehicle Speed Detection using YOLO-V8

## 📖 Description
The **Vehicle Speed Detection using YOLO-V8** project leverages cutting-edge object detection and speed estimation techniques to enhance traffic monitoring and control. The system identifies vehicles and calculates their speed, making it suitable for applications such as traffic regulation and identifying illegal activities like speeding.

---

## 🚀 Key Features
- **Object Detection**: Utilizes YOLO-V8 to identify vehicles in real-time.
- **Speed Estimation**: Calculates speed based on the time elapsed as vehicles cross an imaginary line from the center of the frame.
- **Traffic Control**: Assists in monitoring and regulating traffic flow effectively.
- **Illegal Activity Monitoring**: Helps detect speeding and other traffic violations.

---

## 🔧 Tech Stack
- **Programming Language**: Python
- **Libraries Used**:
  - `CV2` (OpenCV) for video processing and visualization.
  - `Ultralytics` for YOLO-V8 implementation.
  - `pandas` for data handling and analysis.

---

## 🧠 How It Works
1. **Object Detection**:
   - YOLO-V8 identifies vehicles in video frames with high accuracy and speed.
2. **Speed Calculation**:
   - Vehicles' positions are tracked as they cross an imaginary line from the center of the frame.
   - Speed is estimated based on the distance traveled over the elapsed time.
3. **Output**:
   - Displays vehicle speed and detection results in real-time.
   - Logs data for analysis and reporting.
