# Checksum Calculator 🛡️
A fast, 100% private, client-side utility to generate and verify file checksums. Built to handle massive files securely without ever uploading your data to a server. 

Built with 💚 by **@GoldDanger**

![App Preview]### 🟢 Create & Verify Engine
![Create Checksum](create.jpg)
![Verify Checksum](verify.jpg)


## 🤔 Why This Exists
Built to solve the lack of reliable, local-processing bulk checksum tools on mobile devices. I needed a way to verify massive data archives directly from a phone without relying on slow cloud uploads or sketching third-party servers. 

## 📱 Two Editions Available:

### 1. The Web App (Recommended)
A lightweight Progressive Web App (PWA) that runs instantly in your browser. 
* **Live Link:** https://golddanger.github.io/checksum-calculator/
* **Features:** Installable to your home screen, automatic HTTPS clipboard support, and blazing fast CDN routing.

### 2. The Offline Air-Gapped Edition
A heavy-duty, standalone HTML file with the entire 3,000-line crypto engine embedded directly inside.
* **File:** `Checksum_Calculator_Offline.html`
* **Features:** Bypasses CORS restrictions, requires zero internet connection to run, completely immune to CDN outages. Perfect for secure vault storage. Download this file and open it in any browser while in Airplane mode.

## 💡 Use Cases
* **Validate Massive Backups:** Check file integrity after moving data to external drives, Terabox, or local storage.
* **Verify Downloaded ROMs/ISOs:** Ensure your system files and media aren't corrupted.
* **Secure Cross-Device Transfers:** Confirm files match exactly before deleting the originals.

## ⚙️ Supported Algorithms
* SHA-256 (Recommended)
* SHA-512
* SHA-1
* MD5 (Included for legacy file verification)
