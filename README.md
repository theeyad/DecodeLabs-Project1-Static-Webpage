# Moto Luxury Motorcycles — Visual Architecture & Technical Integrity

A high-fidelity static webpage showcasing **Moto Custom Motorcycles**, a premium digital showcase built in strict compliance. 

The project focuses on semantic HTML integrity, BEM methodology, and mathematically exact layout geometry.

---

## What the Project Is

This project is a static homepage for **Moto Custom Motorcycles**, a bespoke performance superbike developer. The layout is built exactly according to the DecodeLabs blueprint and consists of four main sections:
1. **Header (`<header>`)**: A fixed `80px` height navigation bar with a high-fidelity brand logotype on the left and a minimalist navigation menu (`Home`, `NavAce`, `Links`, `Contact`) on the right.
2. **Hero Section (`<section class="hero-container">`)**: A full viewport height (`100vh`) landing stage centered within a `1200px` boundary, featuring an expressive typographic Oswald heading and a sliding call-to-action button.
3. **Content Grid (`<section class="content-cards">`)**: A staggered, symmetrical 12-column grid showcasing six detailed mechanical and design aspects of Moto custom superbikes through six `<article>` cards.
4. **Footer (`<footer>`)**: A solid `400px` height contact info block containing detailed phone numbers, studio locations, and semantic metadata.

---

## Technologies Used

* **HTML5 (Semantic Markup)**: Hand-crafted, valid semantic tags only (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`) to optimize document accessibility and layout readability. Employs a single `<h1>` tag in accordance with SEO heading tree standards.
* **Vanilla CSS3**: Pure, high-performance styling that strictly isolates structure from presentation.
  * **Macro Grid**: A mathematically precise 12-column Grid with `24px` gutter and a `60px` row margin. Grid container padding is locked to `8px` on desktop, guaranteeing that each 3-column card module renders at exactly **`278px`** width.
  * **Micro Flexbox**: Flexbox containers manage micro-alignments inside the header navigation, card horizontal columns, buttons, and footer.
  * **Design Tokens & HSL Colors**: Pure black `#000000` backgrounds combined with bright white `#ffffff` and neutral grey `#a0a0a0` text values, easily exceeding standard contrast ratios (`> 4.5:1`).
  * **BEM Methodology**: Clean BEM methodology (`Block__Element--Modifier`) for consistent, DRY, and scalable styling selectors.
  * **Micro-Animations**: Smooth, lightweight transitions on hover states for links, primary buttons, and card borders.
* **Optimized Image Formats**: Fully compressed high-density **WebP** image assets with explicit width/height dimensions to eliminate Cumulative Layout Shift (CLS), and a **AVIF** favicon.

---

## Quality Metrics Achieved

* **W3C Validation**: Fully validated with zero errors or warnings at `validator.w3.org`.
* **Google Lighthouse**: Achieved a **perfect 4x100 score** across Performance, Accessibility, Best Practices, and SEO.
* **ID Styling Rules**: Contains exactly zero ID styling selectors in `style.css` in accordance with production stylesheet architectures.
