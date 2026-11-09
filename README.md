# 🔐 Password Generator

A clean, responsive **random password generator** built with **vanilla HTML, CSS, and JavaScript** — no frameworks, no libraries, no build step. Pick a length, choose which character types to include, and generate a strong password instantly.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📌 Project Type

| | |
|---|---|
| **Category** | Frontend utility / Mini web app |
| **Type** | Static single-page application (SPA-style, no routing) |
| **Purpose** | Generate random, customizable passwords in the browser |
| **Dependencies** | None |
| **Build Tools** | None — runs directly in the browser |

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (Flexbox, CSS variables-free custom styling, media queries) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Roboto |
| Hosting | Any static host (GitHub Pages, Netlify, Vercel) |

---

## ✨ Features

- 🔢 **Adjustable password length** (2 – 30 characters)
- 🔠 **Toggle character sets** — uppercase, lowercase, numbers, symbols
- ♻️ **Auto-generates a password** on page load
- ⚡ **Instant regeneration** with a single click
- 🌈 **Modern neon/glassmorphism UI** with gradient background and glow effects
- 📱 **Fully responsive** — optimized for mobile, tablet, and desktop
- 🧩 **Zero dependencies** — one HTML file, one CSS file, one JS file

---

## ⚙️ How It Works

1. The script collects the selected character sets (`A-Z`, `a-z`, `0-9`, `~!@#$%^&*()_+/`).
2. It recursively appends one random character from each enabled set until the password reaches the requested length.
3. The result is truncated to the exact length and rendered in the password box.

> **Note:** This project uses `Math.random()` for simplicity (it is an educational/demo project). For production-grade passwords, prefer the Web Crypto API (`crypto.getRandomValues()`).

---

## 📁 Project Structure

```
PasswordGenerator/
├── index.html        # UI markup
├── css/
│   └── custom.css    # Styling, animations, responsive rules
└── js/
    └── app.js        # Password generation logic
```

---

## 🚀 Getting Started

No installation required.

```bash
# 1. Clone the repository
git clone https://github.com/faisalrlakhany/PasswordGenerator.git

# 2. Open the project
cd PasswordGenerator
```

Then simply open `index.html` in your browser — or use VS Code's **Live Server** extension.

---

## 🧠 Concepts Practiced

- DOM manipulation with `getElementById`
- Event listeners and form inputs (`checkbox`, `number`)
- Recursion and string manipulation
- Responsive design with media queries
- CSS gradients, `box-shadow` glow, and `clamp()` for fluid typography

---

## 👨‍💻 Author

**Faisal Raza Lakhany**
GitHub: [@faisalrlakhany](https://github.com/faisalrlakhany)
