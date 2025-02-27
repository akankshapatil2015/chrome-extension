# My Reads Chrome Extension
A simple Chrome extension that allows users to store and manage URLs. This extension captures the current tab's URL and stores it in local storage. Users can also manually enter URLs and delete all saved URLs with a double-click.

🔗 Live Demo: 
Check out the live version of the My Reads Chrome Extension here:  
[My Reads Chrome Extension](https://akankshapatil2015.github.io/chrome-extension/)

---

## Features
✅ Save Current Tab's URL – Click on the "Save Tab" button to store the active tab’s URL.
✅ Add URLs Manually – Users can enter URLs manually and add them to the saved list.
✅ Clear All URLs – Double-click the "Delete All" button to remove all stored URLs.
✅ Persistent Storage – URLs are stored in the browser's local storage and persist across sessions.

---

## Installation

### **Clone the repository:**
```bash
git clone https://github.com/akankshapatil2015/chrome-extension
```

### **Navigate to the project directory:**
```bash
cd chrome-extension
```

- **Load the extension in Chrome:**
- **Open Chrome and go to chrome://extensions/.**
- **Enable Developer mode (toggle on the top right).**
- **Click on Load unpacked and select the project directory.**
- **The extension should now appear in the Chrome toolbar.**

---

## Project Structure
```
|-- index.html
|-- styles.css
|-- script.js
|-- README.md
```

### 📂 index.html – Popup UI for the Chrome extension.
### 🎨 style.css – Styles for the popup UI.
### 📜 index.js – JavaScript logic for capturing, storing, and managing URLs.

---

## How to Use
- **🚀 Save Current Tab**: Click the "Save Tab" button to store the current tab’s URL.
- **📝 Add URL Manually**: Enter a URL in the input field and click "Save Input" to add it to the list.
- **🔗 View Saved URLs**: Click on a saved URL in the list to open it in a new tab.
- **🗑️ Clear All URLs**: Double-click the "Delete All" button to remove all stored URLs.

---

## Development
- Prerequisites: Basic knowledge of HTML, CSS, and JavaScript.
- Uses Chrome APIs to interact with browser tabs and local storage.

---

## 🤝Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.
