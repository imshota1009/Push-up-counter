# 💪 Push-up Counter ✨

A web application that uses your webcam and AI-based pose estimation to automatically count push-ups in real time.  
Track your workouts accurately at home — no gym required!  

👉 Start here: https://imshota1009.github.io/Push-up-counter/

<div align="center">
  <img src="images/push_up_screenshot.png" alt="Push-up Counter Screenshot">
</div>

---

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-8B4513?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-6A0DAD?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

---

## ✨ Features

- **AI-powered automatic counting**  
  Uses TensorFlow.js (MoveNet) to detect body joints and determine push-up movements based on elbow angle.  

- **Real-time feedback**  
  Displays current count, arm state (UP/DOWN), and simple feedback on screen.  

- **No installation required**  
  Works directly in your web browser — no extra software needed.  

- **Privacy-friendly**  
  All camera processing happens locally in the browser. No video is sent to external servers.  

- **Responsive design**  
  Works on PC, tablet, and smartphone.  

---

## 🚀 How To Use

1. **Open the file**  
   Open `pushup_counter.html` in your browser.  

2. **Allow camera access**  
   When prompted by the browser, click **Allow**.  

3. **Get ready**  
   - Wait a few moments for the AI model to load.  
   - Face your body sideways to the camera.  
   - Adjust distance so shoulders, elbows, and wrists are visible.  

4. **Start training**  
   - From a bent position (elbows < 90° → DOWN) to a fully extended arm (UP) counts as **one push-up**.  

5. **Reset**  
   - Use the **Reset** button to return the counter to 0.  

---

## 💡 Tips for Better Accuracy

- Exercise in a well-lit environment  
- Keep the background simple  
- Wear clothing that makes body lines easy to detect  
- Adjust the camera so your full upper body and arms are visible  

---

## 🛠️ Tech Stack

- **HTML / CSS / JavaScript** – Core structure and logic  
- **TensorFlow.js** – Machine learning library running in the browser  
- **Pose Detection (MoveNet)** – Pose estimation model  
- **Tailwind CSS** – UI styling  
