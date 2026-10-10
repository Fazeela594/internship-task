# Hunar – Freelancing Marketplace Landing Page

Hunar ("skill" in Urdu) is the landing page of a freelancing marketplace where clients can find freelancers for web, design, mobile, data and marketing work. Built as a Week 1 internship task with HTML5, CSS3 and vanilla JavaScript.



## Features

- **Navigation bar:** brand logo, Home, Find Freelancers, Find Jobs, About, and Login/Register buttons. It stays fixed at the top, highlights the section you are viewing, and becomes a hamburger menu on mobile.
- **Hero section:** platform introduction, a tabbed search bar ("Search for services" / "Search freelancers"), quick-search tags, and animated platform stats.
- **Popular categories:** Web Development, Graphic Design, Mobile App Development, Data Analysis and Digital Marketing. Clicking a category filters the freelancer cards.
- **How it works:** three-step explanation of the platform.
- **Freelancer cards:** generated from a JavaScript data array, with live search, category filter chips, sorting (top rated, lowest rate, highest rate), and a save (heart) button.
- **Empty state:** a message and a "Clear filters" button when no freelancer matches.
- **Login/Register modal:** form validation, switch between login and register, closes with Esc or a click outside.
- **Footer:** links and copyright.
- **Responsive design:** desktop, tablet (up to 960px) and mobile (up to 700px).
- **Accessibility:** keyboard focus styles, ARIA labels, and reduced-motion support.

## Technologies

- HTML5
- CSS3 (Grid, Flexbox, CSS variables, media queries)
- JavaScript (DOM manipulation, event delegation, IntersectionObserver)

## Project structure

```
├── index.html   # page structure
├── style.css    # layout, design and responsive styles
└── main.js      # data, filtering, search, modal and interactions
```

## How to run

1. Download or clone the repository.
2. Keep `index.html`, `style.css` and `main.js` in the same folder.
3. Open `index.html` in a browser (or use the VS Code Live Server extension).

## Screenshots

Add your desktop, tablet and mobile screenshots here, for example:

```
![Desktop view](screenshots/desktop.png)
![Tablet view](screenshots/tablet.png)
![Mobile view](screenshots/mobile.png)
```

## Author

Fazeela Manzoor ([@Fazeela594](https://github.com/Fazeela594))
