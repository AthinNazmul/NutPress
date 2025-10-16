# 🔔 NutPress — The Ultimate Bachelor Doorbell

> “A real man never knocks on doors… he presses the nuts!” 😎  
> Forget boring doorbells. This is **NutPress** — a fun and smart **bachelor home doorbell system** powered by **Firebase** and a sleek web dashboard.

---

## 🚀 Project Overview

NutPress is a playful IoT-inspired project that replaces the traditional doorbell with a web-based notification system.  
When someone arrives at your bachelor pad, they just need to **press the NutPress button** — and everyone gets notified instantly with sound, vibration, and a colorful log on the screen.  

It’s built for **fun, creativity, and laughs** — but it’s also a good example of **real-time communication using Firebase Realtime Database** and **front-end event handling**.

---

## 🧠 Features

- 🎵 **Sound + Vibration Alerts:** Plays a sound and vibrates your device when the NutPress is pressed.  
- 🌈 **Animated Interface:** Beautiful glowing UI with animated gradients, shadows, and wiggle effects.  
- ⚡ **Real-Time Firebase Updates:** Every press instantly syncs across all connected clients.  
- 💬 **Funny Bachelor Mode:** Hilarious quotes and fun design to match the “bachelor house” vibe.  
- 📱 **Responsive Design:** Works perfectly on phones, tablets, and desktops.  
- 💾 **Press History Log:** Keeps a colorful timeline of all button presses with timestamps.

---

## 🧩 Tech Stack

| Component | Technology Used |
|------------|-----------------|
| Frontend | HTML, CSS (Animations, Flexbox, Gradients) |
| Backend | Firebase Realtime Database |
| Audio | Custom `.wav` sound file |
| Browser API | Vibration API for mobile feedback |

---

## ⚙️ Setup Instructions

1. **Clone this repository:**
   ```bash
   git clone https://github.com/<your-username>/NutPress.git
   cd NutPress
   ```

2. **Add your Firebase credentials:**
   Inside the `<script>` tag of your HTML file, replace:
   ```js
   const firebaseConfig = { ... };
   ```
   with your own Firebase app configuration.

3. **Run locally:**
   Just open the `index.html` file in your browser — no server required!  
   You can also host it on Firebase Hosting or GitHub Pages for easy sharing.

---

## 🔊 How It Works

1. When you open the dashboard, click **Activate Notifications** to enable sound and vibration.  
2. Once activated, the **“Press NutPress”** button appears.  
3. Every press sends a timestamp to Firebase, triggering:
   - A **beep sound**
   - A **vibration**
   - A new colorful entry in the press history  
4. Everyone connected sees the same updates instantly.

---



## 🤪 Bachelor Philosophy

> “Doorbells are for families.  
> NutPress is for legends.” 🥜

---

## 🛠️ Future Improvements

- 🔔 Add ESP32 hardware integration to trigger a physical buzzer.  
- 📱 Add push notifications for remote alerts.  
- 🎨 Add user themes (Dark Mode / Party Mode).  
- 🧑‍💻 Make it multi-user with nickname tracking for who pressed the nut.

---

## 💡 Credits

Created with ❤️, laughter, and late-night snacks.  
By Athin — because why knock when you can press the nuts?

---

## 📜 License

This project is released under the **MIT License** — feel free to remix, fork, or improve it!
