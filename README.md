# uzcss-example

This is a demo project showcasing the use of [`uzcss`](https://github.com/usmonovshohruxmirzo/uzcss) — a CSS compiler that lets you write CSS using **Uzbek syntax**.

All styling in this project is done in a single `.uzcss` file: `styles.uzcss`.

## 🌐 Live Demo

**View it here:**
🔗 [https://usmonovshohruxmirzo.github.io/uzcss-example](https://usmonovshohruxmirzo.github.io/uzcss-example)

---

## 🚀 Installation

To run the project locally:

```bash
git clone https://github.com/usmonovshohruxmirzo/uzcss-example.git
cd uzcss-example
npm install
```

---

## 🛠 Usage

To compile the `.uzcss` file into standard CSS:

```bash
npm run uzcss
```

> This will compile `styles.uzcss` into `dist/style.css`.

You can then open `index.html` in your browser to view the site.

---

## 📁 Project Structure

```
uzcss-example/
├── dist/
│   └── style.css        # Auto-generated CSS file
├── src/
│   └── styles.uzcss     # Main stylesheet written in Uzbek syntax
├── index.html           # Demo page
├── package.json         # Project config
└── README.md            # Project documentation
```

---

## 🧪 Features Demonstrated

* Writing CSS properties and values in Uzbek (`rang`, `kenglik`, `balandlik`, etc.)
* Automatic compilation from `.uzcss` to `.css`
* No extra config needed - just run the script

---

## 📦 Related

* 🔧 [`uzcss`](https://github.com/usmonovshohruxmirzo/uzcss) – The compiler itself
