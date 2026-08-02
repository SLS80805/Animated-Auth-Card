# 🔐 Pure CSS Animated Auth Card

A lightweight, modern, and responsive Login & Signup component built entirely with **HTML5** and **CSS3**—zero JavaScript required!

## ✨ Features
- **Zero JavaScript:** Tab switching and form toggling are handled entirely via hidden CSS radio buttons and the general sibling selector (`~`).
- **Semantic HTML5:** Built using `<main>`, `<nav>`, `<form>`, and properly typed input fields (`email`, `password`, `text`).
- **Smooth Animations:** Integrated CSS keyframe transitions (`@keyframes fade`) for form switching and smooth button hover states.
- **Modern Layout:** Centered dynamically using CSS Flexbox with a modern gradient background and rounded input fields.

## 📁 Repository Structure
```text
├── loginpage.html   # HTML markup containing state controllers, tabs, and forms
└── login.css        # Stylesheet containing design layout and CSS tab-switching mechanics

##  🛠️ How It Works
State Control: Hidden <input type="radio"> elements (#login and #signup) hold the active tab state.

Label Binding: Navigational <label> elements target the radio buttons via their for attribute.

Sibling Selection: CSS selectors (:checked ~ #loginform) dynamically switch form visibility (display: block) and apply active button styling depending on which radio button is active.
