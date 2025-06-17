# Hand Tracking in VR

**Hand Tracking in VR** is a Unity-based interactive system that enables natural hand interactions in virtual environments using VR headset sensors. This package demonstrates how to implement hand gesture recognition and interaction without the need for physical controllers.

## ✋ Features

- 👐 **Controller-Free Hand Tracking**
- 🤌 **Gesture-Based Interaction** (grab, pinch, point, etc.)
- 🧱 **Interactive Objects** (grab, move, release, hover)
- 🛠️ **Built with Unity XR & Oculus/Hand Tracking SDKs**

## 📦 How to Use

> This repository provides a Unity `.unitypackage`, not a complete Unity project.

### 1. Create or Open a Unity Project

- Open **Unity Hub**
- Create a new 3D project using **Unity 2021.3 LTS** or later

### 2. Import the Package

- Download and save the provided `HandTracking_VR.unitypackage` file
- In Unity: `Assets > Import Package > Custom Package...`
- Select the `.unitypackage` file and import all contents

### 3. Set Up XR & Hand Tracking

- Install these via **Unity Package Manager**:
  - `XR Plugin Management`
  - `Oculus XR Plugin` (or `OpenXR` with hand tracking support)
- Enable your platform in `Edit > Project Settings > XR Plugin Management`
- For Oculus: enable hand tracking in `Oculus Settings > Input > Hand Tracking Support`

### 4. Build and Run

- Connect your VR headset (e.g., Oculus Quest)
- Use `Build and Run` to test on-device

> ⚠️ Make sure hand tracking is enabled in the headset settings.

## 🧰 Requirements

- **Unity Version:** 2021.3 LTS or later
- **VR Hardware:** Oculus Quest / Quest 2 / Quest Pro or compatible OpenXR device
- **Dependencies:**
  - XR Plugin Management
  - Oculus Integration (or OpenXR)
  - Hand Tracking APIs

## 🗂️ Included in the Package

- 📁 Scenes/
- 📁 Scripts/ (Hand tracking logic, gesture detection)
- 📁 Prefabs/ (Hand visualizers, interactable objects)
- 📁 Materials/ and UI/


## 📄 License

This package is intended for demonstration, research, or learning purposes. Commercial use of the code or assets may require permission.

---
