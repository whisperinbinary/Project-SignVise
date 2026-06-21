<div align="center">
  <h1><b>SignVise</b></h1>
  <h3><i>An Integrated ML‑Based Platform for Gesture‑Driven Text, Control & Safety with Gamified Learning</i></h3>
  <br/>
  
  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
  [![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)]()
  [![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)]()
  [![Mediapipe](https://img.shields.io/badge/Mediapipe-0082FB?style=for-the-badge&logo=google&logoColor=white)]()
</div>

<hr/>

## 🚨 **Problem Statement**
- **Inaccessibility in Crises**: Emergency situations often prevent manual device interaction.
- **Lack of Automation**: Existing systems lack automated gesture‑based detection.
- **Delayed Response Times**: Absence of real‑time location and visual context delays response.
- **The Need**: A low‑latency, hands‑free AI emergency alert mechanism.

---

## 💡 **Description & Solution**

**SignVise** tackles these challenges by transforming your device's camera into a powerful, hands-free interface.

- **Real-Time Tracking**: Hand landmark recognition powered by **Mediapipe**.
- **Frame Processing**: Video frame processing & gesture duration tracking with **OpenCV**.
- **Emergency SOS**: Emergency alert system leveraging computer vision for sustained gesture detection.
- **Automated Alerts**: Automated SMS delivery via **Twilio API**, integrated with real‑time geolocation tracking.
- **Virtual Control**: Gesture‑based cursor movement module designed for differently‑abled and bed‑ridden individuals.
- **Interactive Education**: Gamified learning experience for gesture recognition to enhance accessibility and engagement.
- **Robust Architecture**: Built with **Python**, ensuring modularity, scalability, and cross‑platform adaptability.

---

## ⚙️ **Workflow Architecture**

Here is a visual representation of how **SignVise** processes inputs and delivers actionable outputs:

```mermaid
graph TD
    A[📷 Webcam Frame] --> B[🤖 Mediapipe Hand Tracking]
    B --> C{🧠 OpenCV Processing}
    
    C -->|Sustained Gesture| D[🚨 Emergency SOS Module]
    D --> E[📍 Fetch Geolocation]
    E --> F[📲 Twilio API SMS Alert]
    
    C -->|Navigation Gesture| G[🖱️ Virtual Mouse Control]
    G --> H[Cursor Movement & Clicks]
    
    C -->|Educational Mode| I[🎮 Gamified Learning]
    I --> J[Interactive ASL Feedback]
```

---

## ⚙️ **Tech Stack**
- **Core Language**: Python  
- **Computer Vision**: Mediapipe, OpenCV  
- **Communication APIs**: Twilio API  
- **Location Services**: Geolocation APIs

---

## 🌍 **Impact**
- 🚑 Enables hands‑free emergency response in critical, life-threatening situations.
- ♿ Provides vital assistive technology and control for differently‑abled users.
- 🎓 Enhances learning and accessibility through a gamified gesture recognition journey.

---

## 📂 **Source Code**

📥 **[Download Source Code (ZIP) via Google Drive](https://drive.google.com/file/d/1InNBP2LUyAILm9k9iiz5uvlqZk4ZTF8k/view?usp=sharing)**  

---

## 🎬 **Demonstration Video**
📥 **[Download Demo Video](https://github.com/whisperinbinary/SignVise/raw/refs/heads/master/demo/Project%20SignVise%20Demo%20Video.mp4)**

---

## 💼 **LinkedIn Post**
🔗 **[View LinkedIn Update](https://www.linkedin.com/feed/update/urn:li:activity:7428827759898140672/)**

---

## 👥 **Contributors**

| Name | Role | Socials |
|------|------|---------|
| **Atal Sharma** | Project Lead & Backend (Chatbot & SOS Module) | [LinkedIn](https://www.linkedin.com/in/atal-sharma-2659aa370/) |
| **Harshit Sharma** | Backend Development (Text‑to‑Speech Module) | [LinkedIn](https://www.linkedin.com/in/harshit-sharma-4a167237b/) |
| **Abhishek Sharma** | Backend Development (Virtual Mouse Module) | [LinkedIn](https://www.linkedin.com/in/abhishek-sharma-765322370/) |
| **Pratyush Daspattnaik** | Frontend Development | [LinkedIn](https://www.linkedin.com/in/pratyush-daspattnaik-3b1a46366/) |

---

## 📷 **Project Visuals**

<p align="center">
  <img src="docs/demo%203.jpeg" width="250" style="margin: 10px; border-radius: 10px;"/>
  <img src="docs/demo%202.jpeg" width="250" style="margin: 10px; border-radius: 10px;"/>
  <img src="docs/Screenshot%20(4).png" width="250" style="margin: 10px; border-radius: 10px;"/>
</p>

<p align="center">
  <img src="docs/Screenshot%20(5).png" width="250" style="margin: 10px; border-radius: 10px;"/>
  <img src="docs/Demo.jpeg" width="250" style="margin: 10px; border-radius: 10px;"/>
</p>

---

> **⚠️ Disclaimer:** This repository hosts the deployed application for demo purposes. Please note that any errors occurring due to incorrect user implementation or environmental misconfigurations must not be inferred as a development error.

---

<div align="center">
  <i>Built by the Team PRAGYAAN</i>
</div>
