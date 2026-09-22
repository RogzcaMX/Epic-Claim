<div align="center">

<p align="center">
  <a href="README.md">
    <img src="https://img.shields.io/badge/%F0%9F%8C%90%20Leer%20en%20Espa%C3%B1ol-FA9191?style=for-the-badge&logoColor=black&labelColor=FA9191" height="42" alt="Leer en Español">
  </a>
</p>

<br>

<h1 align="center">
  🎮 Epic-Claim
</h1>

### Claim your free Epic Games on Android in 2 or 3 taps

[![Release](https://img.shields.io/github/v/release/RogzcaMX/Epic-Claim?color=6366f1&style=for-the-badge&logo=android)](https://github.com/RogzcaMX/Epic-Claim/releases)
[![License](https://img.shields.io/badge/License-Open%20Source-emerald?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android-blue?style=for-the-badge&logo=android)](https://www.android.com/)
[![Ko-Fi](https://img.shields.io/badge/Ko--Fi-Buy%20a%20Coffee-ff5e5b?style=for-the-badge&logo=kofi)](https://ko-fi.com/rogzca)

<p align="center">
  <b>Epic-Claim</b> was created for those of us too lazy to turn on the PC or open a browser every week just to claim Epic Games giveaways. Specially designed if you manage multiple accounts and hate constantly logging in and out.
</p>

[Download APK (Latest Version)](https://github.com/RogzcaMX/Epic-Claim/releases) • [Website](https://rogzcamx.github.io/Epic-Claim/) • [FAQ](#-frequently-asked-questions)

</div>

---

## ✨ Key Features

- 👥 **Unlimited Multi-Account Support:** Link as many accounts as you want and switch between them with a single tap from the top bar.
- ⚡ **Fast Assisted Claiming:** Opens the $0 checkout directly with your session injected via cookies. Just confirm and mark the claim.
- 📦 **"In Library" Badge:** Instantly see if the active account already claimed the current title so you don't waste time or mobile data.
- 📜 **Independent History per Account:** Each profile keeps its own claimed games log with date, time, and real-time search.
- 🔔 **Background Alerts:** Automated notifications powered by `WorkManager`. Schedule them for the weekly Epic reset (Thursdays 15:00 UTC), every 24 hours, or set your custom time.
- 🔒 **100% Private & Local:** No external servers or cloud databases. Your sessions are stored locally and encrypted on your device using `EncryptedSharedPreferences` (AES-256).
- 🎨 **Full Customization:** Light theme, manual dark mode, follow system, or schedule by time. English and Spanish support.

---

## 📱 How does the claiming process work?

1. **Add your account:** Sign in once using the integrated secure webview to store your session cookies.
2. **Check weekly games:** The app fetches the catalog directly from Epic Games Store's official promotions API.
3. **Claim in 2 taps:** Tap **Claim**, and the app takes you straight to the $0 checkout page with your session active. Confirm the order on Epic Games and tap the green checkmark (✓) to log it into your history.
4. **Switch:** Switch to your next account from the top menu and repeat within seconds.

---

## 📥 Download & Installation

1. Go to the [GitHub Releases](https://github.com/RogzcaMX/Epic-Claim/releases) section.
2. Download the `.apk` file for the latest release (e.g., `Epic-Claim.v1.0.Archikos.apk`).
3. Open the file on your Android device and allow installations from unknown sources if prompted.
4. You're ready to go! Start linking your accounts.

---

## ❓ Frequently Asked Questions

<details>
<summary><b>Why doesn't the app fully automate the claiming process?</b></summary>
<br>
Epic Games uses anti-bot protections (hCaptcha) and payment gateways requiring human interaction to prevent automated abuse. Epic-Claim bypasses all tedious navigation and injects your session so you only have to confirm the final order.
</details>

<details>
<summary><b>Can the developer view my passwords or accounts?</b></summary>
<br>
No. The application has no intermediary servers, databases, or connection with the developer. Authentication happens directly with Epic Games servers, and cookies are stored solely within your device's encrypted storage.
</details>

<details>
<summary><b>Why does it ask me to renew my session after a few days?</b></summary>
<br>
Epic Games invalidates tokens and session cookies periodically for security reasons. When this happens, simply tap <i>Restart Account Session</i> in the account menu to refresh your credentials without losing your claim history.
</details>

---

## ☕ Support & Donations

Epic-Claim is a personal, free, and open-source project. If it saves you time week after week, feel free to buy me a coffee:

<div align="center">
  <a href="https://ko-fi.com/rogzca" target="_blank">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Support on Ko-Fi">
  </a>
</div>

---

## 📬 Contact

- **Bug reports & issues:** `soporte_rogzca@yahoo.com`
- **Feedback & suggestions:** `feedback_rogzca@yahoo.com`

---

<div align="center">
  <sub>Crafted with care by <b>Rogzca</b> with Gemini AI assistance.</sub><br>
  <sub>This project is not affiliated, endorsed, or associated with Epic Games, Inc.</sub>
</div>
