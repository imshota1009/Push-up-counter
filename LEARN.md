# 📘 LEARN.md

Welcome to **Push-up Counter** 💪  
This document is for learning purposes — to help you understand the core technologies and concepts behind this project.  
By exploring the code and following this guide, you can learn practical AI + web development skills.

---

## 🌱 What You’ll Learn

- How to use **TensorFlow.js** in the browser  
- How **pose detection (MoveNet)** works to estimate body joints  
- How to access and use the **webcam with JavaScript**  
- How to analyze **elbow angles** to detect push-ups  
- How to provide **real-time feedback** with simple UI/UX design  

---

## 📸 Pose Detection with MoveNet

This project uses **MoveNet**, a fast pose estimation model provided by TensorFlow.js.

### Key Concepts
- Pose estimation detects **17 body landmarks** (shoulders, elbows, wrists, etc.)  
- By calculating the **angle of the elbow**, we can determine if the arm is "UP" (extended) or "DOWN" (bent).  
- Repetition counting is based on detecting the transition from DOWN → UP.  

👉 Learn more: [TensorFlow.js Pose Detection Docs](https://www.tensorflow.org/js/models?hl=en#pose-detection)

---

## 🎥 Webcam Access with JavaScript

The app uses the **MediaDevices API** to access your camera.  

```js
navigator.mediaDevices.getUserMedia({ video: true })
  .then(stream => {
    videoElement.srcObject = stream;
  });
