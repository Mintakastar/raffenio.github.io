# Rafael López Ibarra - Online Curriculum Vitae

This repository contains the source code for the online Curriculum Vitae of Rafael López Ibarra, a Senior Java Developer and Tech Lead.

## 🌐 Live Demo
The live version of this CV is accessible at: [raffenio.dev](https://raffenio.dev)

## ✨ Features
*   **Modern Design**: Premium dark mode aesthetic with smooth animations.
*   **Responsive Layout**: Fully responsive design that works seamlessly across desktop, tablet, and mobile devices.
*   **Interactive Timeline**: Visual representation of work experience with company logos.
*   **Skill Visualization**: Animated skill bars showcasing technical expertise.
*   **Local Assets**: Company logos and fonts are served locally for performance and reliability.
*   **Downloadable PDF**: Direct link to download the traditional PDF version of the CV.

## 🛠️ Technology Stack
This project is built using core web technologies for maximum performance and flexibility:
*   **HTML5**: Semantic markup for structure and accessibility.
*   **CSS3**: Custom styling with CSS variables, Flexbox, CSS Grid, and animations. No heavy CSS frameworks were used.
*   **Vanilla JavaScript**: Lightweight interactions and scroll animations using `IntersectionObserver`.

## 📂 Project Structure
```text
/
├── index.html          # Main HTML structure and content
├── style.css           # Styling rules, animations, and responsive design
├── main.js             # JavaScript logic for scroll effects and animations
└── img/            # Directory containing locally stored company logos
    ├── 3-pillar-global.png
    ├── adsum.jpeg
    ├── capgemini.svg
    ├── epam-neoris.jpeg
    ├── epam.svg
    ├── neoris.png
    └── tcs.svg
└── assets/            # Directory containing assets
    └── rafael-lopez-cv.pdf  # Downloadable PDF version of the CV
```

## 🚀 Running Locally
To run this project locally, simply clone the repository and open the `index.html` file in your preferred web browser. No build steps or local servers are required.

## 📝 Editing the CV
To update the CV content:
1.  **Text Content**: Edit `index.html` to update text, dates, or add new experiences.
2.  **Styling**: Modify `style.css` to adjust colors, fonts, or layout.
3.  **Logos**: Add new SVGs to `src/img/` and update the corresponding `<img>` tags in `index.html`.
4.  **PDF**: Replace the PDF file and update the download links in `index.html`.

## 📄 License
This project is for personal use as a portfolio.
