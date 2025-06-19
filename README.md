
---

# 🖐 Gesture-Controlled Volume Control Using OpenCV & MediaPipe

A real-time hand gesture-based system that lets you control your computer's system volume using the distance between your thumb and index finger, using only your webcam.

---

## 📌 Project Overview

This project demonstrates how computer vision and audio control APIs can be used to create **touchless interfaces**. By detecting specific hand landmarks through a webcam, the system measures the distance between your fingers and dynamically adjusts your system volume accordingly.

---

## 🚀 Features

* 🖐 Real-time hand detection and tracking
* 📏 Distance-based volume control (thumb to index finger)
* 🎛 System volume control using Pycaw (Windows only)
* 🎥 Real-time webcam feed with FPS monitoring
* 📦 Lightweight and runs efficiently on most systems

---

## 🧠 Technologies Used

| Technology     | Purpose                                |
| -------------- | -------------------------------------- |
| **Python**     | Programming language                   |
| **OpenCV**     | Video capture and image processing     |
| **MediaPipe**  | Real-time hand tracking and landmarks  |
| **Pycaw**      | Windows audio control API              |
| **Math/Logic** | Euclidean distance for gesture control |

---

## 📷 How It Works

1. **Hand Detection**: MediaPipe detects 21 landmarks on your hand.
2. **Landmark Tracking**: The system tracks the thumb tip (`id 4`) and index finger tip (`id 8`).
3. **Distance Calculation**: Calculates the Euclidean distance between these two points.
4. **Volume Mapping**: Maps the distance to volume level (normalized using Pycaw).
5. **Live Feedback**: Displays the result with real-time FPS on screen.

---

## 📽️ Demo Preview

> Coming Soon – Add a GIF or screen recording showing how the volume increases and decreases with finger movements.

---

## 🧪 How to Run

### 🔧 Requirements

* Python 3.7+
* Windows OS (due to `pycaw`)
* Webcam

### 📦 Install Dependencies

```bash
pip install mediapipe opencv-python pycaw comtypes
```

### ▶️ Run the Script

```bash
python gesture_volume_control.py
```

> Press `q` to quit the application.

---

## 🛠️ Future Enhancements

* ✨ Add machine learning models to recognize complex gestures (e.g., mute, pause, play)
* 🗣 Integrate voice commands for hybrid control
* 🌐 Cross-platform audio control support (Linux/Mac)
* 📲 Use mobile camera or Raspberry Pi for embedded system applications
* 🧠 Deep Learning (CNNs) for robust gesture classification

---

## 🧩 Use Cases

* Smart home media control
* Touchless systems in public or medical settings
* Accessibility support for differently-abled users
* Integration in AR/VR and gaming environments

---

## 🤝 Contribution

Feel free to fork the repository and submit a pull request with improvements. Whether it’s bug fixes, new features, or enhancements — contributions are welcome!

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Ankit Vishwakarma**
📧 [ankitvishwakarma4591@gmail.com](mailto:ankitvishwakarma4591@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/ankit-vishwakarma-324baa2a6/)
🌐 [Portfolio](https://gqr.sh/uFqa)

---