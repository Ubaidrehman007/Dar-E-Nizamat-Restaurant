# 🍽️ Royal Spice Restaurant Website

A multi-page, fully static restaurant website engineered strictly using **100% pure HTML5**. Built as an academic practice project, this repository demonstrates structural markup, multi-page navigation, nested table layouts, form design, and traditional HTML presentation attributes without relying on external CSS or JavaScript frameworks.

## 📌 Project Overview

**Royal Spice Restaurant** represents a 4-page fictional culinary website built to showcase core web development foundations.

The primary focus centers on:

- **Semantic Layout Architecture:** Utilizing native HTML5 structural tags such as `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`.
- **Structured Data Layouts:** Implementing HTML tables for menus, schedules, and split-column sections.
- **Seamless Navigation:** Cross-linking multiple HTML pages using relative paths.
- **Interactive Form Elements:** Capturing user input using native form elements such as inputs, dropdowns, and textareas.
- **Attribute-Based Styling:** Designing the interface using HTML presentation attributes such as `bgcolor`, `color`, `bordercolor`, `cellpadding`, and `cellspacing`.

> ⚠️ **Note:** This project intentionally excludes CSS, JavaScript, Bootstrap, and backend integration to fulfill strict academic HTML-only criteria.

---

## 📄 Pages & Architecture

| Page | File Name | Key Sections / Features |
|---|---|---|
| 🏠 **Home** | `index.html` | Restaurant introduction, special dishes, opening hours, customer testimonial, and restaurant image. |
| 🍴 **Menu** | `menu.html` | Starters, Main Course, Desserts, and Beverages with descriptions, prices, and images. |
| 👨‍🍳 **About** | `about.html` | Restaurant story, mission, vision, Head Chef information, and image gallery. |
| 📞 **Contact** | `contact.html` | Restaurant contact information, reservation form, and location/map section. |

---

## 🎨 Visual Palette & Design Theme

The website follows a warm restaurant-inspired visual theme designed around cream backgrounds, brown typography, and golden accents.

| Role | Color Name | HTML / Hex Value | Visual Context |
|---|---|---|---|
| **Main Background** | Antique White | `antiquewhite` | Main page background |
| **Primary Text** | Black | `black` | Paragraphs, lists, and table content |
| **Headers & Links** | Saddle Brown | `saddlebrown` | Navigation and headings |
| **Visited Links** | Sienna | `sienna` | Visited navigation links |
| **Accent** | Goldenrod | `goldenrod` | Highlights and star ratings |
| **Dividers & Borders** | Gray | `gray` | Horizontal rules and table borders |

---

## 🛠️ Technologies & HTML Elements Used

### HTML5 Semantic Elements

The project uses the following HTML elements:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<footer>`
- `<table>`
- `<tr>`
- `<th>`
- `<td>`
- `<form>`
- `<input>`
- `<textarea>`
- `<select>`
- `<option>`
- `<ul>`
- `<li>`
- `<a>`
- `<img>`
- `<hr>`
- `<br>`

### HTML Presentation Attributes

Since the project is intentionally built without CSS, HTML presentation attributes are used for basic visual formatting:

```text
bgcolor
color
align
valign
width
height
border
bordercolor
cellpadding
cellspacing
face
size
```

---

## 📁 Repository Structure

```text
Royal-Spice-Restaurant/
│
├── index.html                  # Main homepage
├── menu.html                   # Food & beverage menu page
├── about.html                  # Brand story & gallery page
├── contact.html                # Contact & reservation page
│
├── images/                     # Static media assets
│   ├── Restaurant.jpg.jpeg     # Restaurant interior image
│   ├── royalchef.png           # Head chef profile picture
│   ├── Restaurantfront.png     # Restaurant exterior
│   ├── dining.png              # Dining area
│   ├── footcounter.png         # Food counter
│   ├── sweet.png               # Dessert image
│   └── RestaurantInter.png     # Restaurant interior
│
└── README.md                   # Repository documentation
```

---

## 🔗 Multi-Page Navigation Flow

All four pages are connected using relative HTML hyperlinks through a common navigation section.

```html
<nav>
    <table width="100%" border="0" cellpadding="8" cellspacing="0">

        <tr>

            <td align="center">

                <font face="Arial" size="4">

                    <a href="index.html">Home</a>
                    &nbsp; | &nbsp;

                    <a href="menu.html">Menu</a>
                    &nbsp; | &nbsp;

                    <a href="about.html">About</a>
                    &nbsp; | &nbsp;

                    <a href="contact.html">Contact</a>

                </font>

            </td>

        </tr>

    </table>
</nav>
```

---

## 🚀 Getting Started

Because this project relies exclusively on standard HTML5, no package installation, build process, or backend server is required.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Royal-Spice-Restaurant.git
```

### 2. Navigate to the Project

```bash
cd Royal-Spice-Restaurant
```

### 3. Launch the Website

Open:

```text
index.html
```

in any modern web browser.

You can also use **VS Code + Live Server**:

1. Open the project folder in VS Code.
2. Open `index.html`.
3. Right-click the file.
4. Select **Open with Live Server**.

---

## 📚 Learning Objectives Achieved

This project demonstrates practical understanding of:

1. Constructing HTML5 web documents.
2. Using semantic HTML elements.
3. Creating multi-page websites.
4. Connecting pages using hyperlinks.
5. Creating structured layouts using HTML tables.
6. Working with images and `alt` attributes.
7. Creating forms using native HTML controls.
8. Using HTML attributes for basic visual presentation.
9. Organizing static assets using folders.
10. Building a complete static website without CSS or JavaScript.

---

## 🎓 Academic Profile

- **Project:** Static Restaurant Website
- **Developer:** Ubaid Rehman
- **Degree Program:** B.Tech in Computer Science & Engineering
- **Technology:** Pure HTML5
- **Project Type:** Academic / Educational

---

## ⚠️ Project Limitations

This project is intentionally restricted to HTML.

Therefore:

- ❌ No CSS
- ❌ No JavaScript
- ❌ No Bootstrap
- ❌ No frontend frameworks
- ❌ No backend
- ❌ No database
- ❌ No real online reservation processing

The reservation form is currently a static HTML form intended for demonstration and academic purposes.

---

## 📜 License

This repository is created solely for educational and academic showcase purposes.
