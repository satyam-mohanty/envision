**# Envision – Real-Time AI Accessibility Assistant**

Envision is an AI-powered mobile application built to support visually impaired users with real-time scene understanding.  
Using on-device camera input and cloud-based Gemini vision models, Envision provides instant spoken descriptions of the user’s surroundings to improve safety, awareness, and independent mobility.

---

**## 🚀 Features**

### 🔹 Real-Time Environment Analysis  
Envision continuously captures camera frames every few seconds and sends them to an AI vision model for interpretation.  
It delivers short, precise descriptions of obstacles, objects, text, and surroundings.

### 🔹 Voice Output (TTS)  
All scene descriptions are spoken aloud using the device’s built-in Text-to-Speech engine.

### 🔹 Haptic Feedback  
Short vibration pulses notify the user when a new description is available.

### 🔹 Background Processing  
Vision analysis runs in intervals without blocking the UI, making the experience smooth and reliable.

### 🔹 Clean, Minimal UI  
The interface is designed for ease of use: large touch targets, high contrast, and simplified navigation.

---

**## 🛠️ Tech Stack**

- **Kotlin (Android)**  
- **CameraX API** for continuous frame capture  
- **Retrofit + OkHttp (REST calls)** for handling Gemini API requests  
- **Gemini 2.5 Flash Vision** and newer models  
- **Coroutines** for async work  
- **Text-to-Speech** for real-time voice feedback  
- **Haptic Engine (Vibrator)** for tactile alerts  

---

**## 🧠 How It Works (Workflow)**

1. App captures an image using CameraX.  
2. Bitmap is converted to Base64 and sent to Gemini Vision.  
3. AI returns a concise description.  
4. App speaks it aloud using Text-to-Speech.  
5. A short haptic pulse confirms output.  
6. Loop repeats automatically.

---

**## 🧭 Target Users**

Envision is built for:

- Visually impaired individuals  
- Elderly users needing environment cues  
- Situations requiring hands-free scene awareness  

---

**## 🛡️ License**

This project is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 (CC BY-NC-ND 4.0)**.  
You may use and share the code, but **commercial use, modification, or redistribution is not allowed**.

Full license text:  
https://creativecommons.org/licenses/by-nc-nd/4.0/

---

**## 📸 Demo (Coming Soon)
**
Screenshots, demo videos, and UI previews will be added after the final UI is completed.

---

## 🧑‍💻 Author

**Satyam Mohanty** 
Passionate about AI, accessibility, and human-centered technology.

---

## ⭐ Contribute

This project is currently closed-source for modifications.  
Feel free to submit issues or suggestions.


