# Personal Portfolio - Muhammad Rafi A Syifaa

This repository contains the source code for my personal portfolio and digital branding website.

The purpose of this website is to serve as a digital resume, project gallery, and primary contact point for potential employers, clients, and collaborators to understand who I am and what I've worked on.

**[Visit the Live Site Here](https://revou-fsse-oct25.github.io/milestone-1-mrafiasyifaa/)**

![Frontpage View](assets/images/Website_Overview.png)
---
![Mobile View](assets/images/Website_Overview_Mobile.png)

---

## 🚀 Overview

As a developer, building a digital presence is key. This website represents my professional platform to:
* **Showcase Projects:** Document and exhibit my technical work in the Software Engineering field.
* **Share My Story:** Provide context about my background, skills, and professional interests.
* **Be a Point of Contact:** Make it easy for anyone to connect with me via the contact form or social media.

---

## ✨ Key Features & Implementation

This website has been upgraded from a basic HTML structure to a fully responsive, styled, and interactive experience.

### 1. Responsive & Visual Design (CSS3)
* **Mobile-First Approach:** The site is designed primarily for mobile devices and scales up for desktops using CSS Media Queries (`@media (max-width: 768px)`).
* **Advanced Layouts:**
    * **CSS Grid:** Used in the **About Section** to create a dynamic "bento-style" photo gallery (1 large image, 2 stacked small images) and for the **Project Gallery** layout.
    * **CSS Flexbox:** Used for the main header, navigation alignment, and centering content in the Hero section.
* **Consistent Branding:** Utilization of **CSS Variables** (`--primary-color`, `--accent-color`, `--font-main`) ensures consistent coloring and typography throughout the site.
* **Responsive Images:** All images utilize `object-fit: cover` and relative widths to ensure they scale perfectly within their containers without distortion.

### 2. Navigation & Interactivity (JavaScript)
* **Hamburger Menu (Mobile):**
    * On smaller screens, the navigation links collapse into a slide-in drawer menu to save screen space.
    * Controlled via a JavaScript toggle function that adds/removes an `.active` class.
* **Background Music Widget:**
    * **Global Controls:** A play/pause button (`▶`/`⏸`) located in the header.
    * **Playlist Dropdown:** A toggleable UI allowing users to choose between "Relaxing" and "Adventurous" tracks.
    * **Logic:** Built with Vanilla JS to handle audio states and prevent autoplay blocking issues.
* **Functional Contact Form:**
    * Includes frontend validation and a JavaScript-handled submission simulation that resets the form and shows a success message without reloading the page.

### 3. Accessibility (A11y)
* **Semantic HTML:** Proper use of `<header>`, `<nav>`, `<main>`, `<article>`, and `<footer>` for screen reader optimization.
* **ARIA Attributes:** Added `aria-label` to icon-only buttons (like the Music and Hamburger buttons) to describe their function to non-visual users.
* **Screen Reader Utilities:** Implementation of a `.sr-only` class to provide labels for form elements (like the Language dropdown) without cluttering the visual design.

---

## 🛠️ Technology Stack

* **HTML5 (HyperText Markup Language)**
    * **Role:** Semantic structure and content organization.
    * **Key Features:** Semantic tags, `<audio>` elements, and accessibility attributes (`aria-label`, `role`).

* **CSS3 (Cascading Style Sheets)**
    * **Role:** Visual styling and responsive layout.
    * **Key Features:** **External CSS** file (`index.css`), CSS Grid, Flexbox, CSS Variables (`:root`), Transitions/Animations, and Media Queries for responsive breakpoints.

* **JavaScript (Vanilla JS - ES6+)**
    * **Role:** Interactive functionality.
    * **Key Features:** DOM Manipulation (`classList.toggle`), Event Listeners, and Audio API control. No external frameworks were used.

---

## 📁 Running The Project Locally

You can run a copy of this project on your local machine for testing or development.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/revou-fsse-oct25/milestone-1-mrafiasyifaa.git](https://github.com/revou-fsse-oct25/milestone-1-mrafiasyifaa.git)
    ```
2.  **Navigate to the Project Folder**
    ```bash
    cd milestone-1-mrafiasyifaa
    ```
3.  **Open the `index.html` File**
    * Simply double-click the `index.html` file.
    * No server or dependencies needed.

---

## 🔮 Future Features

This website is an evolving project. Here are some features planned for future updates:

* **Language Switch Functionality:** Enable the "English/Bahasa Indonesia" dropdown button to dynamically change the text content.
* **Dark Mode Toggle:** Add a switch to toggle between light and dark themes using CSS variables.
* **Project Detail Pages:** Create dedicated pages for each project case study.
* **Backend Integration:** Connect the contact form to a real email service (e.g., EmailJS or a Node.js backend).

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KTVBmApB)