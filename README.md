# 🤖 Social Auto-Liker Pro

A browser extension to automate interactions on **LinkedIn** and **Instagram**, designed for educational and experimental purposes.

---

## ✨ Features

This extension provides a range of automation features for both LinkedIn and Instagram, all configurable from the extension popup.

### 🔗 LinkedIn

-   ❤️ **Auto-Like Posts:** Automatically likes posts in the LinkedIn feed.
-   👥 **Auto-Connect:** Sends connection requests to people.
-   ➕ **Auto-Follow:** Follows profiles.
-   💬 **Auto-Like Comments:** Likes comments on posts.

### 📸 Instagram

-   ❤️ **Auto-Like Posts:** Automatically likes posts in the Instagram feed.

---

## 📦 Installation

### 1. Download the Extension

You can either clone this repository or download it as a ZIP file and extract it to a local folder.

### 2. Load as an Unpacked Extension in Chrome

1.  Open Chrome and navigate to `chrome://extensions/`.
2.  Enable **Developer Mode** using the toggle switch in the top-right corner.
3.  Click the **Load unpacked** button.
4.  Select the folder where you cloned or extracted the extension files.

---

## 🚀 How to Use

1.  Navigate to either **LinkedIn** or **Instagram**.
2.  Click the extension icon in your browser's toolbar to open the popup.
3.  In the popup, select the platform you are currently on (LinkedIn or Instagram).
4.  Configure the settings, such as the daily like limit and the speed of the automation.
5.  Click the **Start** button to begin the automation.

The extension will now perform the selected actions on the current page. You can **Pause** or **Stop** the extension at any time from the popup.

---

## 📁 Project Structure

```
.
├── manifest.json
├── background.js
├── content-linkedin.js
├── content-instagram.js
├── popup.html
├── popup.js
├── options.html
├── options.js
├── styles.css
└── icons/
```

-   `manifest.json`: Defines the extension's permissions and structure.
-   `background.js`: The service worker for the extension, managing background tasks.
-   `content-linkedin.js`: The content script that runs on LinkedIn pages.
-   `content-instagram.js`: The content script that runs on Instagram pages.
-   `popup.html` & `popup.js`: The UI and logic for the extension's popup.
-   `options.html` & `options.js`: The UI and logic for the extension's settings page.

---

## ⚠️ Disclaimer

-   This extension is built for educational purposes only.
-   Using automation tools on social media platforms may violate their terms of service.
-   The developers of this extension are not responsible for any misuse or any issues with your social media accounts.

---

## 📄 License

This project is licensed under the MIT License.
