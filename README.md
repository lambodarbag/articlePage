# 📄 Responsive Article Page – README

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![Responsive-Design](https://img.shields.io/badge/Responsive-Design-brightgreen)

> A clean, responsive article page with a CSS-only mobile navigation menu — perfect for beginners and frontend learners.

This project is a **responsive article webpage** built using **HTML + CSS only**. It includes a navigation bar with a mobile-friendly **CSS-only hamburger menu toggle**, a heading, text content, and an image section.

---

## 🚀 Features

### ✅ Responsive Navigation Bar

* Desktop view shows all navigation links.
* Mobile view shows a **hamburger menu icon**.
* Clicking the icon opens a dropdown containing the menu links.
* Clicking the close icon hides the menu again.
* All interactions implemented using **pure CSS** (no JavaScript).

### 🎨 Styling

* Uses **Montserrat** Google Font.
* Smooth box shadows.
* Hover effects for navigation links.
* Mobile-friendly layout with reordered content.

### 📱 Mobile Optimization

* Navigation becomes toggle-based.
* Font sizes and layout adjust under `480px` width.
* Image and text stack vertically.

---

## 📂 File Structure

```
project-folder/
│
├── index.html       # Main HTML file
├── styles.css       # All styling + responsive menu toggle
├── menu.png         # Hamburger icon
└── close.png        # Close icon for mobile menu
```

---

## 🧩 How the Menu Toggle Works (CSS Only)

The project uses a **hidden checkbox** to control the menu:

```html
<input type="checkbox" id="menuToggle" class="menu-toggle">
```

* When the checkbox is **unchecked**, only the hamburger icon is visible.
* When **checked**, the navigation panel becomes visible.
* CSS sibling selectors (`+` and `~`) detect the checkbox state.

## 📦 Usage

1. Place `index.html`, `styles.css`, `menu.png`, and `close.png` in the same folder.
2. Open **index.html** in any browser.
3. Resize the browser to see mobile responsiveness.

---

## ✨ Customization

You can easily:

* Change colors
* Replace fonts
* Modify animation speed
* Add more navigation links
* Adjust box shadows and layout

---

## 👨‍💻 Credits

Made by **Ayush** — designed for responsive UI learning.
