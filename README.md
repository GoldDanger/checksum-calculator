![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

# Checksum Calculator 🛡️
A fast, 100% private, client-side utility to generate and verify file checksums. All processing happens locally — your files never leave your device.

Try It Instantly - https://golddanger.github.io/checksum-calculator/

Built with 💚 by **@GoldDanger**

| Create Engine | Verify Engine |
| :---: | :---: |
| ![Create](create.jpg) | ![Verify](verify.jpg) |

## 💡 Why This Exists
I needed a reliable bulk checksum tool for mobile, but I couldn't find one that was simple and effective. Using complex Termux commands every time I wanted to check a file was too much friction. I built this tool to make the process easy for myself and to help others who want a clean, powerful, and private way to handle file integrity on the go.

## 📱 Two Editions Available

### 1. The Web App (Recommended)
A lightweight Progressive Web App (PWA) that runs instantly in your browser. 
* **Live Link:** https://golddanger.github.io/checksum-calculator/
* **Features:** Installable to your home screen, automatic HTTPS clipboard support, and blazing fast processing.

### 2. The Offline Air-Gapped Edition
A standalone HTML file with the Self-contained crypto engine (fully offline, no dependencies) embedded directly inside.
* **File:** `Checksum_Calculator_Offline.html`
* **Features:** Bypasses CORS restrictions, works with zero internet, and is perfect for secure storage. Download it and open it in any browser while in Airplane mode.

## 🛠️ Use Cases
* **Verify Downloads:** Ensure your ROMs, ISOs, or media files aren't corrupted.
* **Check File Integrity:** Confirm files match exactly after moving them between folders or devices.
* **Backup Validation:** Quickly verify that a copied file is a perfect match of the original.

## ⚙️ Supported Algorithms
* **SHA-256** (Recommended)
* **SHA-512**
* **SHA-1**
* **MD5** (For legacy verification)

## 🛡️ Security & Trust
Because this is a standalone Progressive Web App (PWA) and not a commercial app from the Google Play Store, Android may show a "Play Protect" or "Older Version" warning during installation.

**Why this happens:**
* **No Tracking:** This app is 100% private and does not contain the tracking/telemetry code Google uses to "verify" apps.
* **WebAPK Generation:** Android re-wraps the code into a local "WebAPK" every time you install it, which can trigger generic system warnings.
* **Open Source:** The best security is transparency. You can audit every line of code in `index.html` and `sw.js` right here in the repository to see that your data never leaves your device.

**Verdict:** If prompted, it is safe to select "Install anyway" or "Scan app." Once scanned, Play Protect will confirm the app is clean.
