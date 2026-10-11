<h1 align="center">Sunshine Café</h1>

<p align="center">
  A three-page static website for a fictional coffee shop, written in plain HTML and CSS.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Responsive-yes-6F4E37?style=for-the-badge" alt="Responsive">
</p>

## About

Sunshine Café is a small front-end practice project, built while learning the fundamentals of HTML
page structure and CSS layout. It is a multi-page site for an imaginary café with a shared header,
navigation and footer, a full-width hero, a priced menu and a contact page, all styled from a single
stylesheet with a warm coffee-brown palette.

Concepts practised: semantic HTML (`header`, `nav`, `main`, `section`, `footer`), multi-page
navigation, an overlay hero with absolute positioning and `transform`, `object-fit` images, Flexbox
menu cards, and a mobile breakpoint with a media query.

## ✨ Pages & features

- 🏠 **Home** (`index.html`): hero image with a centred overlay, tagline and a "View Menu" call to action, plus a short About section.
- ☕ **Menu** (`menu.html`): *Coffee & Drinks* and *Pastries* sections with image, description and price for each item.
- 📍 **Contact** (`contact.html`): address, opening hours, phone and email.
- 🧭 Shared navigation bar and footer on every page.
- 📱 Responsive: menu cards stack vertically below 768px.

> The nav bar also links to `login.php` and `register.php`; those back-end pages are not part of this repository.

## 🛠 Tech stack

- HTML5
- CSS3 (Flexbox, media queries); one shared `style.css`
- No JavaScript, no frameworks, no build step

## 🏗 Project structure

```text
├── index.html     # Home
├── menu.html      # Menu
├── contact.html   # Contact
└── style.css      # Shared styles
```

## 🚀 Getting started

```bash
git clone https://github.com/youssef336/Cafe_html.git
cd Cafe_html
open index.html                  # or double-click it / serve with: python3 -m http.server 8000
```

Images are loaded from external URLs, so an internet connection is needed to see them.

## 👤 Author

**Youssef Belal Zakaria** · [GitHub @youssef336](https://github.com/youssef336)

⭐ If you like this project, give it a star!
