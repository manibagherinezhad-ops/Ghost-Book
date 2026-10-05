# 📖 Ghost 

> An interactive 3D book animation built from scratch with **HTML & CSS**, featuring perspective effects and CSS hover interactions.

---

## 🖤 About The Project

**Ghost Book** is a small front-end project created to practice and showcase **CSS 3D effects, perspective, positioning, and interactive animations**.

The project presents a simple book-like composition using two layered images and CSS transforms to create the illusion of a three-dimensional book.

When the user hovers over the book, the entire object rotates in 3D, revealing its depth and creating a page-opening effect.

The project focuses on achieving a visual interaction using **CSS alone**, without JavaScript.

---

## 🌐 Live Demo

📖 **[View the Live Website](https://manibagherinezhad-ops.github.io/Ghost-Book/)**

---

## 🎴 Features

* 📖 **3D Book Effect**
  A book-like composition created using CSS 3D transforms, perspective, and layered images.

* 🌀 **3D Perspective Rotation**
  The book uses CSS `perspective()` and `rotateY()` to create a three-dimensional visual effect.

* 🖱️ **Hover Interaction**
  Hovering over the book triggers a smooth rotation animation that changes its viewing angle.

* 📐 **CSS 3D Transformations**
  The project uses `transform-style: preserve-3d`, `translateZ()`, `rotateY()`, and perspective effects to create depth.

* 📄 **Book Edge Effect**
  A repeating linear gradient is used to create a visual representation of the pages along the side of the book.

* 🖼️ **Layered Images**
  Two separate images are positioned and layered to form the front and back surfaces of the book.

* 🎨 **Minimal Visual Design**
  The project keeps the surrounding interface simple so the main focus remains on the 3D book interaction.

* ⚡ **No JavaScript**
  The entire interaction is created using HTML and CSS without JavaScript.

---

## 🛠️ Built With

* 🌐 **HTML5**
* 🎨 **CSS3**
* 🌀 **CSS 3D Transforms**
* 📐 **CSS Positioning**
* 🖱️ **CSS Hover States**
* 🎞️ **CSS Transitions**
* 🌈 **CSS Gradients**

---

## 📂 Project Structure

```text
Ghost-Book/
│
├── index.html
│
├── assets/
│   └── css/
│       └── master.css
│
└── img/
    ├── Wenay_Anime.jpg
    └── download.jpg
```

---

## 🌀 How It Works

The main element of the project is the `.Book` container.

The book starts with a rotated perspective:

```css
transform: perspective(800px) rotateY(-30deg);
```

When the user hovers over it, the rotation changes:

```css
transform: perspective(800px) rotateY(-150deg);
```

The book also uses:

```css
transform-style: preserve-3d;
```

to maintain the three-dimensional positioning of its child elements.

The second image is moved backward along the Z-axis using:

```css
transform: perspective(800px) translateZ(-150px);
```

Together, these properties create the depth and layered appearance of the book.

---

## 📐 CSS Techniques

This project was created to experiment with several CSS techniques:

* `perspective()`
* `rotateY()`
* `translateZ()`
* `transform-style`
* `transform-origin`
* `transition`
* `:hover`
* `::after`
* `position: absolute`
* `object-fit`
* `repeating-linear-gradient()`

These techniques work together to create the 3D book effect without relying on JavaScript.

---

## 🎯 Purpose

This project was created as a **front-end practice project** to improve skills in:

* HTML structure
* CSS positioning
* CSS 3D transformations
* Perspective effects
* Hover interactions
* CSS transitions
* Pseudo-elements
* Layered elements
* Z-axis positioning
* CSS gradients
* Visual composition
* Creating interactive effects without JavaScript

---

## 🎨 Design Direction

The design intentionally keeps the surrounding interface minimal.

A simple gray background allows the book itself to become the main visual element.

The focus of the project is not a complex page layout, but the relationship between **perspective, depth, rotation, and layered imagery**.

The visual result is a small interactive experiment that turns a simple pair of images into a three-dimensional object.

---

## 👨‍💻 Author

### Mani Bagherinezhad

**Front-End Developer**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/manibagherinezhad-ops)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/mani-bagherinezhad-641217350/)

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge\&logo=instagram\&logoColor=white)](https://www.instagram.com/manibagherinezhad_dev/)

---

## 🧑‍🏫 Mentor

### Parsa Ghorbanian

**Mentor**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/parsaGhorbanian)

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge\&logo=instagram\&logoColor=white)](https://www.instagram.com/parsa_ghorbanian_web/)

[![Web Design Course](https://img.shields.io/badge/Web_Design_Course-4285F4?style=for-the-badge\&logo=google-chrome\&logoColor=white)](https://trainingsitedesign.ir/learn-web-design/)

---

## ⚠️ Disclaimer

This project is created for **educational and portfolio purposes**.

The images used in the project belong to their respective creators and copyright holders.

This project is not affiliated with or endorsed by the creators or owners of the original artwork used in the images.

---

### 📖 *"Every page has another side."*

**Made with HTML, CSS & 📖**
