# 🇳🇱 Nederlandse Werkwoorden (Offline Dutch Verb Conjugator)

A lightweight, 100% offline-first web app and PWA for Dutch verb conjugations containing over **4,700+ verbs**.

---

## 📖 About This Project

Hi! I am currently learning Dutch (Nederlands). While studying, I constantly needed a fast and reliable tool to check verb conjugations on the go — especially when commuting or in places without stable internet access. 

Unfortunately, I couldn't find a clean, completely offline application that had an extensive collection of Dutch verbs without requiring a paid subscription or heavy third-party app installations. 

To solve this problem, I built this application! 

> **Disclaimer:** I have very limited coding experience. I built and designed this entire project with the assistance of **AI** to create an efficient, distraction-free tool that anyone learning Dutch can benefit from.

---

## ✨ Features

- **📚 4,700+ Verbs:** Comprehensive coverage of Dutch regular and irregular verbs.
- **⚡ Instant Principal Parts:** Quickly shows the three essential forms at the very top of each verb:
  - **Infinitief** (Infinitive)
  - **OVT** (*Onvoltooid Verleden Tijd* / Simple Past - singular & plural)
  - **VD** (*Voltooid Deelwoord* / Past Participle)
- **📴 100% Offline (PWA):** Once opened, it caches assets locally. You can use it in airplane mode or with no internet connection.
- **🚀 Ultra-low Memory & Storage footprint:**
  - Total download size is only around **~11 MB**.
  - Uses chunk-based lazy loading so older devices (like iPhone X) use virtually zero RAM and run smoothly without lag or crashes.
- **🌓 Dark Mode & Mobile Friendly:** Fully responsive design that respects your system's light/dark mode preference.

---

## 📱 How to Use & Install on iPhone / iPad (Add to Home Screen)

You can turn this web page into a native-feeling app on your iOS device **without needing the App Store**:

1. Open the website URL in **Safari** on your iPhone or iPad.
2. Tap the **Share** button (the square with an arrow pointing upward at the bottom of the screen).
3. Scroll down and tap **"Add to Home Screen"** (*Zet op beginscherm*).
4. Tap **Add** in the top right corner.

🎉 **That's it!** The app icon will appear on your home screen. When you open it, it opens full-screen without Safari toolbars and works **completely offline**.

---

## 💻 How to Use on Mac / Windows / Android

- **Mac / Windows:** Open the link in Safari, Chrome, or Edge. You can bookmark it or click the "Install" icon in the address bar to install it as a desktop application.
- **Android:** Open in Chrome, tap the 3-dots menu icon, and select **"Install app"** or **"Add to Home screen"**.

---

## 🛠 Local Setup (Optional)

If you wish to run the app locally on your own machine:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
python3 -m http.server 8080
```

Then visit `http://localhost:8080` in your web browser.

---

## 📄 License & Credits
- Verb conjugation structure inspired by linguistic references and educational resources.
- Intended strictly for non-commercial, personal educational use for language learners.
