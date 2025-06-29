# 🚀 AI Article Summarizer Chrome Extension

This is a lightweight Chrome Extension that uses **Gemini AI** to summarize any web article, including content from GeeksforGeeks, MDN, blogs, documentation, or news sites.

Get fast summaries in different formats (brief, detailed, bullet points) without leaving the page.

---

## 📸 Preview

### 🔑 API Key Setup  

---

## 🛠 Features

- 🔍 Summarize any article or webpage in 1 click.
- ✨ Supports **Brief**, **Detailed**, and **Bullet Point** summaries.
- 💾 Save your **Gemini API key** securely.
- 📋 One-click **Copy Summary** button.
- 💡 Works on any website (MDN, GFG, blogs, etc.)

---

## 📦 Project Structure

| File/Folder     | Purpose                                |
|----------------|----------------------------------------|
| `manifest.json`| Chrome extension manifest declaration  |
| `popup.html`   | UI for summary generation              |
| `popup.js`     | Logic to call Gemini API and render UI |
| `content.js`   | Extracts text content from the web page|
| `options.html` | UI for entering Gemini API key         |
| `options.js`   | Stores API key in Chrome Storage       |
| `background.js`| Triggers API key prompt on install     |
| `icon.png`     | Icon for your extension                |

---

## 🧪 How to Use

### Step 1: Setup Gemini API Key
1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Generate an API key.
3. Click the extension icon → Click "Set API Key".
4. Paste your key and click "Save API Key".

### Step 2: Summarize Any Article
1. Open any article (e.g., on MDN, GeeksforGeeks).
2. Click the extension icon.
3. Choose summary type:
   - Brief
   - Detailed
   - Bullet Points
4. Click **"Summarize This Page"**.
5. Read or click **"Copy Summary"** to use it elsewhere.

---

## 🧩 How to Install (Development Mode)

1. Clone or download this repo.
2. Go to `chrome://extensions/` in your Chrome browser.
3. Enable **Developer Mode** (top right).
4. Click **Load unpacked**.
5. Select the project folder.

---

## 🔐 Where is my API key stored?

Your API key is stored securely using `chrome.storage.sync`, and is not accessible by external scripts or websites.

---

## 🧠 Powered By

- [Gemini 1.5 Flash API](https://makersuite.google.com/app/apikey)
- Chrome Extension APIs
- JavaScript, HTML, CSS

---

## 📝 License

This project is for educational and personal use only. Not affiliated with Google.

---

## 💬 Feedback & Improvements

Feel free to contribute or raise issues to improve functionality, design, or add features like multilingual support or export options.

