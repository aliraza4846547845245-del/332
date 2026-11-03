# Sweebe - Real-Time Secure Messaging & VoIP Application 🔒📱

> **A Privacy-First Android Application developed as a BSIT Final Year Project.**

[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com/)
[![Language](https://img.shields.io/badge/Language-Java-orange.svg)](https://www.java.com/)
[![Backend](https://img.shields.io/badge/Backend-Firebase-FFCA28.svg)](https://firebase.google.com/)
[![VoIP](https://img.shields.io/badge/VoIP-ZEGOCLOUD-blue.svg)](https://www.zegocloud.com/)

---

## 📌 Project Overview
**Sweebe** addresses the critical **Privacy Paradox** in modern communication tools like WhatsApp and Signal by completely eliminating the dependency on cellular phone numbers. Instead, users authenticate and establish connections via unique, decentralized **Alphanumeric Unique IDs**.

### 🌟 Key Highlights
- **Zero-Cellular Dependency:** Register and connect without exposing personal contact numbers.
- **Asynchronous Handshake Mechanism:** Absolute inbox spam protection via double-opt-in mutual friend requests.
- **Sub-Second Event Propagation:** Powered by Google Firebase Realtime Database (~115ms latency).
- **HD Voice & Video Calling:** Ultra-low latency P2P communication powered by ZEGOCLOUD SDK.

---

## 🛠️ Architecture & Tech Stack

| Component | Technology / Platform |
| :--- | :--- |
| **Language & IDE** | Native Java (JDK) | Android Studio |
| **UI Framework** | Material Design 3, Jetpack ViewBinding |
| **Backend & DB** | Firebase Realtime Database, Firebase Authentication |
| **Media Storage** | Cloudinary CDN (Image Compression & Fast Delivery) |
| **Real-Time RTC** | ZEGOCLOUD Express Video SDK |

---

## 🔐 Core Features

1. **Unique ID System:** Anonymous registration generating a distinct user identifier.
2. **Asynchronous Request Flow:** Unknown entities cannot send payload data without request acceptance.
3. **Rich Messaging:** Real-time text chats, read receipts, dynamic emoji reactions, and built-in image editing.
4. **VoIP Calling:** Integrated high-definition audio and video calling pipelines.
5. **Security Controls:** Instant block/unblock mechanism with Firebase rule-level access revocation.

---

## 👨‍💻 Author & University Credits

- **Developer:** Muhammad Ali Khokhar
- **Registration ID:** 2K23-IT-41
- **Degree:** Bachelor of Science in Information Technology (BSIT)
- **Institution:** Shaheed Benazir Bhutto University of Veterinary & Animal Sciences (SBBUVAS), Sakrand

---

## 📜 License
This project is open for evaluation and educational demonstration purposes.
