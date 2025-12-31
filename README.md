# 👻 Wraith — Ghost Theme

**Wraith** is a minimal and performance-focused theme for **Ghost**, designed for technical blogging and long-form content.

It is a clean, opinionated fork of the official Casper theme, adapted to fit a professional developer-oriented blog.

---

## 🎯 Project Goals

- Minimal, readable and distraction-free layout
- Excellent performance and accessibility
- Clean typography for technical writing
- Long-term maintainability (no heavy JS, no framework)
- Full compatibility with **Ghost 5.x+**

This theme is primarily used on:
➡️ **https://blog.romain-c.fr**

---

## ✨ Features

- Based on Ghost official **Casper** theme
- French translation
- Responsive and mobile-first
- Multiple feed layouts (Classic / Grid / List)
- Light / Dark / Auto color scheme
- Configurable typography (title & body fonts)
- Flexible header & navigation layouts
- Optimized image sizes and lazy loading
- Fully compatible with Ghost Editor cards
- GScan compliant (Ghost theme validator)

---

## 🛠️ Development Workflow

### Requirements

- **Node.js** ≥ 18
- **Yarn**
- **Ghost CLI** (optional, for local testing)

### Install dependencies

```bash
yarn install
```

### Start development mode

```bash
yarn dev
```

This will:
- Watch CSS and JS assets
- Rebuild files on change
- Enable LiveReload

### Build assets

```bash
yarn build
```

### Run theme validation

```bash
yarn test
```

Strict CI-style validation:

```bash
yarn test:ci
```

---

## 📦 Packaging & Release

Create a production-ready ZIP:

```bash
yarn zip
```

The generated archive can be uploaded directly via **Ghost Admin → Design → Upload theme**.

---

## 🔁 Upstream (Casper)

Wraith is based on the official **Casper** theme by Ghost Foundation.

Upstream repository:
👉 https://github.com/TryGhost/Casper

Only selected updates are manually merged to preserve stability and design consistency.

---

## 📄 License

MIT License.

Original work © Ghost Foundation  
Modifications © Romain Chevrot

---

## 🤝 Contributing

This theme is primarily maintained for personal use.

Issues and pull requests are welcome if they align with the project goals and philosophy.
