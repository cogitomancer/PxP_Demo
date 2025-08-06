# Presence × Pursuit (PxP)

**PxP** is a privacy-conscious presence detection system powered by the proprietary **WiSpy algorithm**. Built for environments that require real-time awareness without invasive surveillance, PxP uses signal-based inference to detect, log, and analyze ambient presence — ethically and intelligently.

🌐 **Live Demo:** [https://pxp-demo.vercel.app](https://pxp-demo.vercel.app)

---

## 🧠 The Vision

> Ambient awareness — not surveillance.

Modern institutions rely on outdated, intrusive systems (e.g., sign-in sheets, cameras, facial recognition) that compromise privacy and accuracy. PxP is built as an ethical alternative: real-time presence monitoring that’s **passive**, **opt-in**, and **non-visual**.

---

## 🚀 Features

- 🔍 **Signal-Based Detection**: Detects presence via MAC address(eventually IMEI), WiFi/Bluetooth signal mapping, and optional heart rate/motion data.
- 📉 **Auto Log-Out**: Automatically logs users out after 60 minutes of absence.
- 💓 **Heart Rate + Motion Integration**: Uses ambient signal inference (e.g. WiFi multipath, mmWave, UWB) to detect motion and physiological patterns — no wearables required.
- 📋 **Real-Time Presence Logs**: Frontend displays user session, motion status, and inferred vitals.
- 🧭 **Consent-Based Web App**: User-initiated opt-in flow, legal compliance, and full transparency.
- 🔐 **No Facial Recognition, No Cameras Required** (camera integration is optional for calibration only).

---

## 🛠️ Tech Stack

| Layer        | Tech Used                    |
|--------------|------------------------------|
| **Frontend** | React (Vite or Next.js via Genspark), Tailwind CSS |
| **Backend**  | Flask (Python)               |
| **Hardware** | Raspberry Pi 5, Pi Camera NoIR Wide (optional) |
| **Algorithm**| Proprietary **WiSpy** engine for ambient inference |
| **Deployment** | Vercel, with future support for Snowflake + edge compute |

---

## 🧪 MVP Scope

This prototype simulates the passive detection workflow with:

- MAC-based signal simulation (no login or user input)
- Clean, Pursuit-style UI with minimal interaction
- Exportable log viewer for session data

---

## 🧩 Use Cases & Industry Applications

| Industry            | Application                                                                 |
|---------------------|------------------------------------------------------------------------------|
| 🎓 Education         | Attendance tracking (e.g. Pursuit program), time-on-site analysis           |
| 🏥 Clinics           | Passive patient/staff presence tracking                                     |
| 🧓👶 Elder/Child Care | Detect prolonged absence or unexpected movement                             |
| 🐕 Pet Monitoring    | Smart home pet tracking without intrusive cameras                          |
| 🛡️ Defense           | Presence authentication in sensitive areas without surveillance             |
| 🧘‍♀️ Fitness          | Integration with heart-rate-based platforms (e.g. Orangetheory)              |
| 🏠 Smart Home        | Motion + presence logging for security and convenience                      |

---

## 🔭 What's Next

- 📱 Mobile App with opt-in onboarding, local logs + cloud sync
- 📈 Time-based analytics + emergency alert system
- 🧱 Snowflake-ready backend + hardened DoD/enterprise deployment
- 🤖 Integration with mmWave or computer vision (for calibration only, never core logic)

---

## ✍️ Author

**Maysa Khedr**  
Systems thinker, AI researcher, and ethical technologist.

---

## 📄 License

Proprietary – For demo and educational use only.  
For inquiries about licensing or collaboration, contact the creator.
