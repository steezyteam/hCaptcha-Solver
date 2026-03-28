# 🧩 Steezy hCaptcha Solver 

![Status](https://img.shields.io/badge/Status-Under%20Development-orange?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
[![Discord](https://img.shields.io/badge/Discord-Steezy%20Team-7289da?style=for-the-badge&logo=discord)]([https://discord.gg/steezyteam](https://discord.gg/hH68zFqUTB))

An advanced, multi-modal **hCaptcha automation framework** designed to handle complex challenges using computer vision and deep learning. From precision sliders to AI-powered image labeling, this solver is built to adapt.

---

## ⚠️ Project Status: IN PRE-ALPHA / UNDER DEVELOPMENT
**This repository is currently a showcase.** The source code is not yet public as we are in the final stages of fine-tuning the AI models and motion data.

> **Current Focus:** Optimizing YOLOv8 Medium weights for "Labeling" tasks and humanizing mouse trajectory data.

---

## ✨ Features (Sneak Peek)

### 🛠 Multi-Task Detection
The engine automatically detects the challenge type and switches logic on-the-fly:
* **Slider (Puzzle):** *Sobel-X* edge detection & *Bilateral Filtering* to find slots through textured noise.
* **Grid (Tetris):** *Adaptive Thresholding* to match block patterns with pixel perfection.
* **Line Completion:** Geometric line-tracing to finish broken segments.
* **Image Labeling:** Powered by **YOLOv8 Medium** + **CLAHE** contrast enhancement to identify animals and objects through anti-AI filters.

### 📂 Smart Sorting & Debugging
The framework organizes every attempt into a local `/captchas` directory for easy monitoring:
* Automated sub-folders: `slider/`, `grid/`, `line/`, `labeling/`.
* High-res `guess.jpg` output showing exactly where the AI "aimed."
* Fully **in-built** no **keys** needed.

### 🧠 Advanced Motion Data
Generates non-linear mouse paths using S-curve easing and randomized jitters to mimic human interaction.

---

## 🚀 Tech Stack

* **Language:** Python 3.9+
* **Vision:** OpenCV, NumPy
* **AI:** Ultralytics YOLOv8 (Medium model)
* **Networking:** Curl_cffi (Advanced TLS fingerprinting)

---

## 🤝 Join & Support the Community

Want to follow the development, see early-access demos, or join the team? Come to our Discord!
Please leave me a star to keep me motivated!

### [🔗 discord.gg/steezyteam]([[https://discord.gg/steezyteam](https://discord.gg/hH68zFqUTB)](https://discord.gg/hH68zFqUTB))

---

## 📸 Screenshots
*Coming soon... check our discord server for updates!*

---

## 📜 Disclaimer
This project is for educational and research purposes only. It is intended to test the limits of modern computer vision. We do not encourage or support the violation of any website's Terms of Service.

---
© 2026 Steezy Team. Built with passion and a lot of coffee.
