# Sidebar Navigation Menu

### ₊⊹ About

This project is a simple, modern side navigation menu, developed with a focus on clean design and usability.
It features interactive icons and smooth animations to create a more engaging experience.
The layout keeps the navigation organized without taking up too much screen space.
I recreated this project as a way to practice front-end development and improve my programming skills.
My goal was to learn from an existing design while exploring interactive interfaces and modern user interface concepts.

https://github.com/user-attachments/assets/5e787100-9d73-4882-bfeb-a06f9b1a1d55

---

### ★ Features

**Visual**

- Floating card in the sidebar with rounded corners and a soft shadow
- Collapsed state showing only icons and an expanded state that reveals the link names
- Smooth width animation when opening and closing the sidebar
- Hamburger icon that turns into a close icon (X) when the menu is open
- Active link highlighted in blue with a glow
- Hover effect over links and the toggle button
- Settings pinned to the bottom of the sidebar
- Light, clean theme using the Poppins font

**Code**

- A single `.open` class controls the entire state of the sidebar
- SVG sprite using `<symbol>` and `<use>`, so each icon is defined once and reused
- The icons use `currentColor`, so they match the text color on hover and when active
- JavaScript switches the menu and close icons by changing the `href` of `<use>`
- Accessibility with `aria-label` and `aria-expanded` on the toggle button
- Active link logic: clicking removes the `on` class from all links and adds it to the clicked link
- Colors stored in custom CSS properties (variables)
- Shared styles for links and buttons using the `:is()` selector
- Column layout with Flexbox, using `flex: 1` on the `nav` element, pushing “Settings” to the bottom

---

### ⚙️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (vanilla)**
- **Google Fonts**: Poppins

---

### 🖿 Project structure

```
sidebar-navigation-menu/
├── assets/
├── index.html
├── script.js
├── style.css
└── README.md
```

---

### 📖 What i learned

- **HTML**: aside, a button and links for the sidebar
- **CSS**: position fixed, box-shadow and border-radius for the floating look
- **CSS**: width transition and overflow hidden to reveal the names
- **JavaScript**: classList.toggle to open and close the sidebar
- **JavaScript**: swapping the hamburger amd close icons
