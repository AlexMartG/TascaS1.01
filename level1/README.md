

# 🗂️ Task S1.01. HTML & CSS — Level 1

Responsive layout built with pure HTML and CSS, fully adapted for desktop, tablet and mobile.

---

## 📄 Description

The goal of this project is to build a complete layout following a given wireframe, applying best practices with Flexbox and CSS Grid. The design must work correctly across three main formats: desktop, tablet and mobile.

---

## 🛠 Technologies

- **HTML5** — Semantic structure
- **CSS3** — Flexbox, CSS Grid, Media Queries

---

## 📁 Project structure

```
├── index.html
├── style.css
└── README.md
```

---

## 🎨 Resources used

- Color palette obtained with [Image Color Picker](https://imagecolorpicker.com/es)

---

## 📐 Breakpoints

| Device | Max width |
|--------|-----------|
| Desktop| > 992px |
| Tablet | ≤ 992px |
| Mobile | ≤ 768px |

The main container has a maximum width of **1200px** (`max-width: 1200px`) and is centered with `margin: 0 auto`.

---

## ⚠️ Challenges faced

- Adjusting element sizes without using a fixed `height`, letting each container adapt to its content.
- Making sure no horizontal scroll appeared at any resolution.
- Managing the overlap between tablet and mobile media queries.

---

## 🚀 How to run the project

1. Clone the repository:
   ```bash
   git clone https://github.com/AlexMartG/TascaS1.01.git
   ```
2. Open `index.html` directly in your browser, or use the **Live Server** extension in VS Code to see changes in real time.

---

## ✅ Best practices applied

- No `height` used on containers with content
- No unnecessary `width: 100%` on `block` elements
- Avoided `display: flex; flex-direction: column` when default vertical behaviour already applies
- No horizontal scroll at any resolution
