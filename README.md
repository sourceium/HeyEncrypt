<div align="center">

# 🔐 HeyEncrypt - Smart Pocket Vault

**An All-in-One Privacy Vault & Developer Web Suite Built with Material 3**

[![Live Demo](https://img.shields.io/badge/Live_Demo-heyencrypt.vercel.app-52E565?style=for-the-badge&logo=vercel&logoColor=black)](https://heyencrypt.vercel.app)
[![Version](https://img.shields.io/badge/Version-1.0V-055B15?style=for-the-badge)](https://github.com/sourceium/HeyEncrypt/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-38BDF8?style=for-the-badge)](./LICENSE)
[![Author](https://img.shields.io/badge/Author-Sourceium_By_HaldarAi-C084FC?style=for-the-badge)](https://github.com/sourceium)

<p align="center">
  <a href="https://heyencrypt.vercel.app"><strong>🚀 Launch WebApp</strong></a> •
  <a href="#-key-features"><strong>✨ Features</strong></a> •
  <a href="#-quick-start"><strong>⚡ Quick Start</strong></a> •
  <a href="#-license"><strong>📄 License</strong></a>
</p>

</div>

---

## 🌟 Overview

**HeyEncrypt - Smart Pocket Vault (1.0V)** is a lightweight, zero-backend, client-side security and developer utility web application created by **Sourceium By HaldarAi** (**Subhojit Haldar**). 

Designed with Google's **`@material/web` (Material 3)** components and a high-contrast dual-tone vault aesthetic, HeyEncrypt combines five everyday privacy and developer tools into a single, fast, mobile-responsive interface—with 100% of your data staying locally on your device.

🔗 **Live Website:** [https://heyencrypt.vercel.app](https://heyencrypt.vercel.app)

---

## ✨ Key Features

| Module | Description |
| :--- | :--- |
| 📝 **My Notes** | Create, search, color-code, and export (`.txt`) notes. Lock sensitive notes behind a custom PIN or Pattern. |
| 🛡️ **Authentication (`/2fa`)** | Dedicated quick-launch 2FA Authenticator workspace (`/2fa/index.html`) for managing time-based one-time passwords. |
| 📦 **APK / Archive Viewer** | Inspect `.apk`, `.zip`, and `.jar` files directly in the browser. Features nested archive navigation, `AndroidManifest.xml` binary string extraction, Hex viewer, in-browser file editing, signature validation warnings, and ZIP/APK export. |
| 🔑 **Password Manager** | Secure vault for storing service credentials with instant search, masked password toggles, and one-click clipboard copy. |
| 🕵️ **Advanced Obfuscator** | Obfuscate and de-obfuscate HTML/JavaScript using 4 methods: *Basic Escape*, *Full Hex Escape*, *Base64 Wrap*, and *Char-Code Mapping*. |
| 🔒 **PIN & Pattern Security** | Dual-mode authentication (4-digit PIN or 9-dot Pattern) with automatic brute-force lockout protection (5 failed attempts) and security question recovery. |

---

## 🎨 Dynamic Vault Themes

Customize the entire interface—including Material 3 tokens, SVG vault icons, pattern canvas, and browser status bar—via **Settings → Change Themes Colour**:

* 🟢 **Green (Default):** Neon Green (`#52E565`) & Dark Forest (`#055B15`)
* 🟣 **Lavender:** Neon Lavender (`#C084FC`) & Royal Purple (`#3B0764`)
* 🟠 **Orange:** Neon Amber (`#FB923C`) & Burnt Orange (`#7C2D12`)
* 🔵 **Blue:** Electric Sky (`#38BDF8`) & Deep Navy (`#0C4A6E`)

---

## 🛠️ Tech Stack

* **UI Framework:** HTML5, CSS3 Custom Properties, [`@material/web`](https://github.com/material-components/material-web) (Material Design 3 Web Components)
* **Archive Engine:** [`JSZip 3.10.1`](https://stuk.github.io/jszip/) for client-side APK/ZIP/JAR parsing and repackaging
* **Typography & Icons:** Google Fonts (`Inter` & `JetBrains Mono`), Font Awesome 6.4
* **Storage:** 100% Local Client-Side Storage (`localStorage` API — zero external database tracking)

---

## ⚡ Quick Start

HeyEncrypt requires **no build step or backend server**. You can run it directly in any modern browser.

### 1. Clone the Repository
```bash
git clone [https://github.com/sourceium/HeyEncrypt.git](https://github.com/sourceium/HeyEncrypt.git)
cd HeyEncrypt
```

### 2. Run Locally
Open `index.html` directly in your browser, or serve the folder using any local static server:

```bash
# Using Python
python -m http.server 8080

# Using Node.js (npx)
npx serve .
```

Then visit `http://localhost:8080` in your browser.

---

## 📂 Project Structure

```text
HeyEncrypt/
├── index.html           # Main HeyEncrypt - Smart Pocket Vault WebApp
├── 2fa/
│   └── index.html       # Standalone 2FA Authentication Module
|   └── site.webmanifest # PWA Web App Manifest
|   └── heart-lock.png   # App Icon / 2FA Authentication Logo
├── tools/
|   └── apkview.html     # tools - Apk Inspector
|   └── encryption.html  # tools - Encryption code
|   └── notes.html       # tools - notes webapp
├── favicon.png          # App Icon / Vault Logo
├── sw.js                # service worker
├── site.webmanifest     # PWA Web App Manifest
├── LICENSE              # MIT License
└── README.md            # Project Documentation
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository (`https://github.com/sourceium/HeyEncrypt/fork`)
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👨‍💻 Author & Credits

* **Developer:** Subhojit Haldar
* **Organization / Brand:** Sourceium By HaldarAi
* **GitHub:** [@sourceium](https://github.com/sourceium)
* **Website:** [https://heyencrypt.vercel.app](https://heyencrypt.vercel.app)

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for more information.
