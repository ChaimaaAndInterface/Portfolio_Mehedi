# Personal Portfolio Website

This project is a single-page personal portfolio website designed to showcase skills, projects, and services. It serves as a professional online presence for potential employers, clients, and collaborators.

## Core Technologies

* **HTML5:** The structure and content of the website are built using semantic HTML5 tags like `<header>`, `<section>`, and `<footer>` for improved SEO and accessibility.
* **CSS3:** All styling, layout, and animations are handled with CSS3. The design is fully responsive, utilizing modern layout techniques like Flexbox and CSS Grid.
* **JavaScript (Vanilla):** All interactive features are implemented with plain JavaScript, without the use of external libraries or frameworks.

## Features

This website includes the following features and sections:

### Global Features

* **Light & Dark Mode:** A toggle button in the header allows users to switch between a light and dark color theme. The user's preference is saved in `localStorage` and remembered on their next visit.

### Page Sections

1.  **Header & Navigation**
    * A "sticky" header that remains fixed at the top of the page on scroll.
    * Contains a logo, navigation links (Home, Services, Projects, Blog, Contact), and the theme toggle.
    * Navigation links provide smooth scrolling to the corresponding page section.

2.  **Hero Section (`#home`)**
    * A two-column layout featuring a main headline, a professional subtitle, and a short paragraph describing skills with a focus on **AI and Cyber Security**.
    * Includes a primary "Call to Action" button and a professional profile image.

3.  **Services Section (`#services`)**
    * A grid of service cards, each containing an icon, a title, and a brief description of a service offered (e.g., "Web Development", "Responsive Design").

4.  **Project Showcase (`#projects`)**
    * A grid of project cards, each displaying a project image, title, short description, and technology tags (e.g., "HTML", "CSS", "JavaScript").
    * Includes links to view the live project or its source code.

5.  **Blog Posts (`#blog`)**
    * A grid of blog post cards, each with a feature image, publication date, title, and a short excerpt.
    * A "Read More" link is provided for each post.

6.  **Footer & Contact (`#contact`)**
    * Contains a call to action to get in touch, an email address styled as a button, links to social/professional profiles (GitHub, LinkedIn), and a copyright notice.

### Floating Features

* **Live Chat Widget:**
    * A circular icon fixed to the bottom-right corner of the screen.
    * Clicking the icon opens a simulated chat window where users can send a message.
    * An automatic, pre-written response is provided to demonstrate the functionality without a backend.

## Design and Layout

* **Responsiveness:** The layout is built with a mobile-first approach, ensuring it is fully responsive and looks great on all devices, from small phones to large desktops.
* **Typography:** The 'Inter' font from Google Fonts is used for a clean, modern, and readable aesthetic.
* **Color Scheme:** A clear color palette is defined with a primary accent color and distinct background/text colors for both light and dark themes.

## File Structure

The project is organized with the following file structure:

```
portfolio-project/
├── index.html
├── style.css
├── script.js
└── assets/
    └── hero_image.jpg
