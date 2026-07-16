# 🧮 Claude Token Counter

A lightweight **Manifest V3 Chrome extension** that helps you track token usage while working with AI chat platforms — right from your browser toolbar.

![Manifest](https://img.shields.io/badge/Manifest-V3-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-yellow)

---

## ✨ Features

- **Two-Tab Interface**
  - 📝 **Text Estimation** — Paste or type any text and get an instant token count estimate.
  - 📡 **API Tracking** — Monitor cumulative token usage across your API calls in real time.
- **BPE-Approximation Tokenizer** — A JavaScript-based tokenizer that approximates Byte Pair Encoding to give quick, reasonably accurate token estimates without hitting an external API.
- **Cumulative Session Tracking** — Usage is tracked across your browsing session using `chrome.storage.local`, so your counts persist as you work.
- **Cyberpunk Neon UI** — A sleek, neon-accented dark interface designed to be easy on the eyes during long sessions.

---

## 📦 Installation

1. **Download or clone this repository**
```bash
   git clone https://github.com/logicforgee/cluade-token-counter.git
```
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable **Developer mode** (toggle in the top-right corner)
4. Click **Load unpacked**
5. Select the project folder you just cloned/downloaded
6. The extension icon should now appear in your Chrome toolbar 🎉

---

## 🚀 Usage

1. Click the extension icon in your Chrome toolbar.
2. Switch between the **Text Estimation** tab and the **API Tracking** tab depending on your need.
3. **Text Estimation:** Paste your text to see an approximate token count instantly.
4. **API Tracking:** View cumulative token usage tracked across your session.
5. All data is stored locally in your browser — nothing is sent to an external server.

---

## 🛠️ Tech Stack

- **JavaScript** — Core extension logic and tokenizer
- **CSS** — Cyberpunk neon-themed styling
- **Chrome Extension APIs** — `chrome.storage.local` for persistent session tracking
- **Manifest V3** — Built on Chrome's latest extension platform

---

## 📁 Project Structure
