# 📲 SMS Bomber

A simple SMS Bomber built with **HTML**, **CSS**, and **Vanilla JavaScript** for educational and testing purposes only.  
Send multiple SMS requests to a phone number using public/test APIs (or your own endpoint).

---

## 🚨 Disclaimer

> This tool is built **strictly for educational use**, testing rate-limiting protections, and personal project demos.  
> **Do not use it to harass, spam, or target individuals or services without permission.**  
> The author takes **no responsibility** for misuse.

---

## ⚙️ Features

- 📱 Easy-to-use UI to input phone number and message count
- 🔁 Loop-based bombing logic using `fetch()` or `XMLHttpRequest`
- 💬 Supports sending test messages via public APIs or your own backend
- 🎨 Clean responsive design with CSS
- ⏱️ Delay between requests to prevent browser freezing

---

## 📂 Tech Stack

- ✅ HTML5
- ✅ CSS3 (no frameworks)
- ✅ Vanilla JavaScript (no libraries)
- 🚫 No backend included — you can add your own API endpoints

---

## 🔧 Usage

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/sms-bomber.git
cd sms-bomber
````

### 2. Open the HTML file

```bash
# Just open in your browser
open index.html
```

---

## ✨ Demo

```html
<input type="text" placeholder="Enter Phone Number" />
<input type="number" placeholder="No. of Messages" />
<button onclick="startBombing()">Start</button>
```

> 💡 Customize `startBombing()` function in `script.js` to call your SMS API or mock endpoint.

---

## 🚀 How It Works

It sends requests to vulnerable endpoints for sms bombing. This is illegal if you do without the consent of owner of the websites' endpoints you are using.

> ⚠️ Replace the endpoints with your testable endpoint.

---

## 📁 Project Structure

```
sms-bomber/
├── index.html
├── style.css
└── script.js
```

---

## 📜 License

This project is licensed under the **MIT License**.
Use responsibly and legally.

---

## 🙋‍♂️ Author

Made with 💻 by [Sarker Ayon](https://github.com/amiayon8)
Connect via [Instagram](https://instagram.com/amiayon8)

---

> “Education is power — use it ethically.”
