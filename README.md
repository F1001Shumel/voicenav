# 🚌 VoiceNav: AI-Powered Transit for the Visually Impaired

[![Built with Gemini](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-blue?logo=google-gemini)](https://deepmind.google/technologies/gemini/)
[![Framework-ReactNative](https://img.shields.io/badge/Framework-React%20Native-61DAFB?logo=react)](https://reactnative.dev/)
[![SDG-10](https://img.shields.io/badge/SDG-10.2%20Inclusion-orange)](https://sdgs.un.org/goals/goal10)

**VoiceNav** is a mobile application that leverages **Gemini Vision AI** to provide real-time, voice-guided navigation for Malaysia's visually impaired community, enabling independent use of public transport.

---

## 👥 1. Repository Overview & Team
| Name | Role | Primary Responsibility |
| :--- | :--- | :--- |
| **Alyas** | Project Lead | Core Development & Backend |
| **Hakim** | UI/UX Design | Figma Prototyping & QA |
| **Shuhada** | Documentation | Technical Strategy & AI Alignment |
| **Brinda** | Multimedia | Video Production & Presentation |

---

## 🌟 2. Project Overview

### ❗ Problem Statement
Blind Malaysians face significant barriers when using public transport, often resulting in limited access to education and employment. Navigating bus stops and identifying the correct transit vehicle remains a dangerous and stressful task without real-time assistance.



### 🎯 SDG Alignment
- **SDG 10.2 (Primary):** Empowering social and economic inclusion for persons with disabilities.
- **SDG 4.5:** Ensuring equal access to education for vulnerable persons.
- **SDG 11.2:** Providing safe, accessible transport systems for all.

### 💡 The Solution
VoiceNav uses **Gemini Vision AI** and **Google Cloud Vision OCR** to identify buses, obstacles, and landmarks. The app translates visual data into immediate voice and haptic feedback, allowing users to travel safely and independently.

---

## 🚀 3. Key Features
- **AI Bus Identification:** Real-time recognition of bus numbers and routes using Gemini 2.5 Flash.
- **Live Movement Alerts:** Tracking bus arrivals and GPS movements with voice notifications.
- **Trip Planning & Safety:** Smart route suggestions between destinations with emergency features.
- **Hands-Free Control:** Simple mic features and gesture-based navigation (swipes and double-taps).
- **Voice Command Bus Selection:** Interrupt announcements by saying route numbers (e.g., "581").
- **Haptic Feedback:** Vibration alerts for safety and directional guidance.

---

## 🛠️ 4. Overview of Technologies

### **Google Technologies**
- **Google Gemini 2.5 Flash API:** Computer vision for real-time scene analysis.
- **Google Maps/Location:** GPS positioning for nearby route detection.
- **Google Cloud Vision:** OCR for reading signage and bus numbers.

### **Supporting Tools**
- **Frontend:** React Native with Expo (TypeScript).
- **Navigation:** Expo Router & PanResponder.
- **Voice Engine:** Expo Speech (TTS) & Web Speech API.
- **Transit Data:** RapidKL API Integration (Mock/Simulated).

---

## 🏗️ 5. Implementation & Workflow

### System Architecture
The application acts as a bridge between the physical world and AI processing, turning visual inputs into accessible audio outputs.



### Workflow Steps:
1. **Initialize:** Load GPS location and establish API connections.
2. **Navigation Options:**
   - **Double-tap:** Quick bus tracking with voice commands (e.g., "Where is bus 581?")
   - **Swipe left:** Activate camera for AI-powered bus identification
   - **Swipe right:** Open trip planning with route suggestions and safety features
3. **Analysis:** Gemini Vision identifies approaching buses and obstacles in real-time.
4. **Feedback:** System announces bus status, routes, and safety alerts via Text-to-Speech (TTS).



---

## ⚠️ 6. Challenges Faced
- **Ambient Noise:** Filtering background traffic sounds to ensure accurate voice recognition.
- **Latency:** Minimizing the delay between camera capture and the AI's audio response for safety.

---

## 💻 7. Installation & Setup

Follow these simple steps to get **VoiceNav** running on your local machine:

| Step | Action | Command / Instruction |
| :--- | :--- | :--- |
| **1** | **Install Node.js** | Download from [nodejs.org](https://nodejs.org). Check version: `node -v` |
| **2** | **Clone Repo** | `git clone https://github.com/Alyas100/voicenav.git` |
| **3** | **Navigate** | `cd voicenav` |
| **4** | **Dependencies** | `npm install` |
| **5** | **Launch** | `npx expo start` |

---

### 📱 Running on your Mobile Device
1. 📥 **Download:** Install the **Expo Go** app from the App Store or Google Play Store.
2. 🔗 **Connect:** Ensure your phone and PC are on the **same Wi-Fi network**.
3. 📸 **Scan:** Use your camera (iOS) or Expo Go app (Android) to scan the **QR Code** in your terminal.

---

## 🗺️ 8. Future Roadmap

Our vision for the next evolution of VoiceNav includes:

* ⌚ **Wearable Integration** *Support for Apple Watch and WearOS to provide haptic vibration alerts directly on the wrist.*
* 📡 **Offline Navigation Mode** *Localized AI processing to ensure safety even in areas with zero internet connectivity.*
* 🗣️ **Personalized Voice Profiles** *Advanced AI training to recognize the user's specific voice amidst heavy traffic noise.*
* 🌏 **Multilingual Support** *Expanding voice guidance to include Bahasa Melayu and other local dialects.*

---
> **Note:** For any issues during installation, please check the [Issues](https://github.com/Alyas100/voicenav/issues) tab.

© 2026 **VoiceNav Team**