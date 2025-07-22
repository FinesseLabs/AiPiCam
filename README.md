# 📸 PiCamGuard AI Surveillance (Beta Phase)

A Raspberry Pi-based camera system for AI-powered motion detection and facial recognition — made for home lab security.

---

## 🔍 Project Purpose

This tool uses a Raspberry Pi model 3b + Ardu Camera Module to:

- Monitor physical space
- Detect motion and faces
- Send alerts to Telegram when an unknown face appears

---

## 🔧 Tech Used / Planned

- Raspberry Pi 5 + Camera Module 3
- OpenCV for face detection
- Python for logic + alerting
- Telegram API for notification
- Optionally: SQLite for known face database

---

## 🔂 Roadmap

- ✅ Live camera feed via `libcamera`
- ✅ Capture photos + video in motion
- 🔲 Integrate face detection using Haar Cascades
- 🔲 Add face comparison and "known faces" DB
- 🔲 Send alert if unknown person detected

---

## 🧠 Future Goals

- Touchscreen display to show live feed + alerts  
- Mobile dashboard or mini web UI  
- Integration with smart speaker for voice alerts

---

## 📝 Notes

- PiCamGuard will be integrated with other Finesse home defense tools  
- Want to add offline-only mode for maximum privacy
