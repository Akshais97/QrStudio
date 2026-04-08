# QR Studio

A minimal, fast, and privacy-friendly QR code generator built with pure HTML, Tailwind CSS, and JavaScript.

Generate QR codes instantly, optionally embed your logo, and download them — all directly in your browser.

---

## 🚀 Live Demo

👉 https://akshais97.github.io/qrstudio/

---

## ✨ Features

* Generate QR codes for any URL
* Drag & drop logo upload (max 200KB)
* Embed logo inside QR code
* Download QR as PNG
* Clean, minimal SaaS-style UI
* Fully client-side (no backend, no tracking)

---

## 🧠 How It Works

* Uses the `qrcode` JavaScript library via CDN
* Generates QR code on a `<canvas>` element
* Optionally overlays uploaded logo at the center
* Allows download using `canvas.toDataURL()`

---

## ⚠️ Disclaimer

Embedding a logo may slightly affect scan reliability depending on its size, contrast, and placement.

For best results:

* Use small, centered logos
* Prefer high contrast designs
* Keep logo size minimal relative to QR

---

## 🛠️ Tech Stack

* HTML5
* Tailwind CSS
* Vanilla JavaScript
* QRCode.js (CDN)

---

## 📂 Project Structure

```id="dqp6vh"
qrstudio/
│── index.html
│── README.md
```

---

## 🪜 Getting Started

1. Clone the repository:

```bash id="gstart"
git clone https://github.com/akshais97/qrstudio.git
```

2. Open the project:

```bash id="gopen"
cd qrstudio
```

3. Run locally:

* Open `index.html` in your browser

---

## 🌍 Deployment

This project is deployed using GitHub Pages.

To deploy your own version:

1. Push your code to a GitHub repository
2. Go to **Settings → Pages**
3. Select:

   * Source: `Deploy from branch`
   * Branch: `main / root`
4. Save and access via:

```id="deployurl"
https://<your-username>.github.io/<repo-name>/
```

---

## 💡 Future Improvements

* Custom QR colors and styles
* Download formats (SVG support)
* QR history (local storage)
* Dynamic QR (editable links)
* Analytics dashboard

---

## 📬 Contact

For feedback or collaboration:

* Email: [akshairofficial@gmail.com](mailto:akshairofficial@gmail.com)

---

## 📄 License

This project is open-source and free to use.

---

## 🙌 Acknowledgements

* QR generation powered by `qrcode` library
* UI inspired by modern minimal SaaS design principles

---

Built with simplicity in mind.
