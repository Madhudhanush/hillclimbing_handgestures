# HillClimbingRacing_handgestures
# Hill Climbing Racer with Hand Gestures 🚗🏁

Welcome to the **Hill Climbing Racer** controlled entirely by hand gestures! This project leverages **OpenCV** and **MediaPipe** to detect and interpret your hand movements, turning your webcam into the ultimate racing controller.

---

## 📋 Table of Contents

1. [🎮 Demo](#demo)
2. [⚙️ Features](#features)
3. [🛠️ Installation](#installation)
4. [🚦 Usage](#usage)
5. [🖐️ Supported Gestures](#supported-gestures)
6. [🐛 Troubleshooting](#troubleshooting)
7. [🤝 Contributing](#contributing)
8. [📄 License](#license)
9. [🙏 Acknowledgements](#acknowledgements)

---

## 🎮 Demo

Click the images below to see interactive demos of each gesture in action!

---

## ⚙️ Features

* 🖐️ **Hand Tracking & Gesture Recognition**: Powered by MediaPipe Hands.
* 📷 **Real-time Video Processing**: Uses OpenCV for live webcam feed.
* 🚗 **Full Racing Control**: Accelerate, brake, and steer using natural gestures.
* 🎨 **Customizable Sensitivity**: Tune detection thresholds for your setup.

---

## 🛠️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/hillclimb-handgestures.git
   cd hillclimb-handgestures
   ```

2. **Create a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the game**

   ```bash
   python hillcar.py
   ```

---

## 🚦 Usage

1. Ensure your webcam is connected and positioned to capture your hand.
2. Launch the game with `python main.py`.
3. Perform gestures (described below) to control the car!

---

## 🖐️ Supported Gestures

| Gesture    | Emoji | Description                              | Demo |
| ---------- | ----- | ---------------------------------------- | ---- |
| Accelerate | 🖐    | Open palm facing camera (fingers spread) |      |
| Brake      | ✊     | Closed fist                              |      |
|            |       |                                          |      |
|            |       |                                          |      |

**Tip**: You can adjust the gesture detection threshold in `config.py` for more reliable recognition under different lighting conditions.

---

## 🐛 Troubleshooting

* **No hand detected?**

  * Ensure your hand is within the webcam view.
  * Check that `mediapipe` and `opencv-python` are installed.

* **Inaccurate detection?**

  * Adjust `MIN_DETECTION_CONFIDENCE` and `MIN_TRACKING_CONFIDENCE` in `config.py`.
  * Improve lighting or plain background.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-gesture`
3. Commit your changes: `git commit -m "Add new gesture support"`
4. Push to the branch: `git push origin feature/new-gesture`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgements

* [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) for powerful hand tracking.
* [OpenCV](https://opencv.org/) for real-time computer vision.
* Emoji for making README more engaging! 🎉


