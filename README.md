# Awesome Design — Portfolio Website
**Live Site:** [Visit My Portfolio](https://ali-design.neocities.org/)

![Portfolio Showcase Screenshot](https://github.com/Md12Ali/Awesome-Design/blob/main/Portfolio/img/101.png?raw=true) 

---

* **Live Site:** [https://ali-design.neocities.org/](https://ali-design.neocities.org/)
* **Repository:** [https://github.com/Md12Ali/Awesome-Design](https://github.com/Md12Ali/Awesome-Design)
* **Author:** Mohammed Ali
* **Course:** Level 5 Diploma in Web Application Development
* **Unit:** Unit 1: User-Centric Front-End Development (Y/650/3525)

---

## 📖 Project Overview
Awesome Design is a professional, functional single-page portfolio website built to showcase my web design capabilities, interactive development process, and creative projects. The application utilizes a smooth-scrolling architecture specifically configured to provide an intuitive flow of information for potential clients, technical recruiters, and collaborators without requiring complex supporting documentation.

The interface is divided into five logical sections: 
* **Hero (Masthead):** Immediate value proposition and call to action.
* **About:** Professional background, core philosophy, and skill summary.
* **Services:** Grid-based presentation of professional capabilities.
* **Portfolio:** Interactive masonry project showcase gallery with hover overlays.
* **Contact:** Direct lead-generation links and communication channels.

---

## 👥 User Stories
The platform was engineered to satisfy the explicit needs of the following target audiences:

* **As a new visitor:** I want the site's purpose and professional identity to be immediately evident upon loading so I can decide whether to explore further.
* **As an employer or recruiter:** I want to navigate past works and technical services seamlessly to evaluate coding proficiency and asset integration.
* **As a mobile user:** I want a fully fluid layout that maintains its structural integrity, typography ratios, and grid alignments across all screen dimensions.
* **As an accessibility-dependent user:** I want descriptive alt text on non-text elements, high color contrast, and clear keyboard/screen-reader navigation so I can browse without barriers.

---

## 🎨 UX & Design Documentation

### Wireframe Structure (Low-Fidelity)
Initial structure and information hierarchy were meticulously sketched in Adobe Photoshop to map out layout components and grid behavior prior to any development:

| Section | Component | Component Description |
| :--- | :--- | :--- |
| **Header** | Sticky Nav | Transparent-to-solid fixed wrapper containing the Brand Logo and responsive anchor jump links. |
| **Hero** | Headline + CTA | High-impact centralized typography layout with a primary "Find Out More" button. |
| **About** | Centered Profile | Structured narrative text detailing training background and local service alignment. |
| **Services** | 4-Column Grid | Dynamic flex elements with custom vector icons, clear headers, and capability summaries. |
| **Portfolio**| Masonry Gallery | Responsive image grid containing custom high-resolution project screenshots with clean overlay elements. |
| **Contact** | Clean Footer Split| Multi-column communication block containing active phone and secure email anchor links. |


  <img src="main/portfolio/img/w.png" alt="Low-fidelity wireframe schematic layout">
  <img src="img/w3.png" alt="Low-fidelity wireframe schematic" >


### Core Design Principles
* **Information Hierarchy:** Structural layout is prioritized with introductory elements at the top scaling down to direct inquiries. Semantic headings (`<h1>`-`<h6>`) are implemented sequentially to convey programmatic importance rather than styling.
* **Typography & Contrast:** Configured clean, high-contrast text layouts leveraging background `#FFFFFF` vs text `#212529` to remain fully accessible and distraction-free, satisfying foundational WCAG contrast guidelines.
* **User Control:** The layout completely avoids intrusive auto-popups, hidden overlays, or auto-playing media channels. Every interactive transition or animation is entirely user-initiated.

---

## ✨ Features
* **Responsive Architecture:** Built on top of a mobile-first fluid framework that transitions seamlessly from small viewports (320px) up to ultra-wide desktop monitors.
* **Smooth-Scroll Navigation:** Programmatic jQuery-easing configuration triggers smooth transitions between content blocks via main navbar links.
* **Accessible Graphics:** Fully semantic image tagging with alternative text profiles for screen readers.
* **Isolated External Routing:** All outward-bound links open safely without hijacking the active window.
* **Directory Cleanliness:** Standardized modular file organization ensuring explicit asset paths.

---

## 🛠️ Technologies Used
* **Markup:** HTML5 (Semantic Structure)
* **Styling:** CSS3 (Custom Responsive Overrides)
* **Framework:** Bootstrap v4.5.3 (Grid, Flexbox Utilities, and Navbar components)
* **Typography:** Google Fonts (*Merriweather*, *Merriweather Sans* combinations)
* **Iconography:** Font Awesome v5.15.1
* **Interactivity:** jQuery v3.5.1, jQuery Easing plugin v1.4.1, Magnific Popup v1.1.0
* **Design Systems:** Adobe Photoshop & Adobe Illustrator (Wireframes, Logo Layouts, and Asset Adjustments)

---

## 📜 Credits & Attribution

### Templates Used
This production build was compiled by structurally intersecting, styling, and customising two open-source developer templates:
* **Start Bootstrap Creative v6.0.4** (Distributed under the MIT License) — Used for core masthead layout, navigation wrapper, and about structure.
* **Start Bootstrap Stylish Portfolio v5.0.9** (Distributed under the MIT License) — Adapted for grid-based services structure and portfolio gallery patterns.

### Customizations Applied
While template layouts provided the initial structural boilerplate, the following modifications were developed independently:
* **Branding & Assets:** Created the custom vector logo (`logo2.png`) and fully realigned file paths to follow lowercase naming conventions across all directories.
* **Content Integration:** Authored and integrated all specific text components across sections matching professional services and local target demographics.
* **UI/UX Reskinning:** Altered the framework color swatches, structural divider elements, and customized responsive break margins via CSS overrides.
* **Code Refactoring & Accessibility:** Overhauled the structural tags to include missing descriptive `alt` tags on all 6 project screenshots, implemented secure external targets, and refactored broken contact paths.

---

## 🧪 Testing Profile & Bug Resolution

### HTML & CSS Validation
To ensure structural compliance and cross-browser parsing consistency, codebases were evaluated using formal validation engines:
* **HTML:** Verified using the official W3C Markup Validation Service.
* **CSS:** Validated against the W3C CSS Validation Service (Jigsaw).

Validation records are saved locally within the asset structure:
* HTML Report: `img/html-validation.png`
* CSS Report: `img/css-validation.png`

### Automated & Manual Test Cases
The platform was systematically tested across Chrome, Firefox, Safari, and Edge browser environments using simulated user journeys:

| Target Component | Testing Action | Expected Outcome | Result |
| :--- | :--- | :--- | :--- |
| **Anchor Navigation** | Clicked all menu elements (`#about`, `#services`, etc.) | Smooth scroll maps viewports directly to targeted headers without clipping content. | ✔ Pass |
| **External Link Isolations** | Engaged external outbound anchor tags | Resource opens cleanly in an isolated new browser instance (`target="_blank"` with `rel="noopener noreferrer"` attributes checked). | ✔ Pass |
| **Viewport Fluidity** | Tested layout responsiveness using Chrome DevTools from 320px up to 1920px | Elements stack cleanly vertically on smaller viewports; grids scale proportionately on tablets; text maintains legibility. | ✔ Pass |
| **Accessibility Compliance** | Verified non-text visual asset arrays via WAVE evaluation tool | Every active imagery asset contains explicit descriptive `alt` string data; zero empty parameters detected. | ✔ Pass |
| **Data Protocol Linking** | Clicked email link wrapper inside the contact section | Properly passes string arrays directly to native local mail clients via `mailto:` protocol without syntax errors. | ✔ Pass |

### Bug Fixes & Developmental Life Cycle
During development, the following technical layout anomalies were tracked, isolated, and permanently resolved:
* **Navbar Mobile Overlap Bug:** On extra-small screens (<480px), the sticky navbar overlay was conflicting with top section padding causing text occlusion. *Resolution:* Configured targeted CSS `@media` rule queries to dynamically downscale text sizes and inflate top element padding bounds on compact screens.
* **Broken Email Route:** The contact block email anchor element failed to route successfully because the raw address was bound directly inside the code snippet. *Resolution:* Prefixed the anchor string with the mandatory `mailto:` protocol constraint (`href="mailto:mohammed_12ali@outlook.com"`).
* **Asset Filename Case Conflicts:** Capitalization patterns within production images (e.g., `.PNG`) caused broken image link flags during remote server testing. *Resolution:* Re-saved and programmatically linked all project imagery to strict lowercase file schemas (`capture1.png`, `logo2.png`).

---

### What I Customised
* All text content (About, Services, Contact details).
* Portfolio gallery populated with my own project screenshots.
* Colour adjustments to match my personal brand.
* Custom logo design and integration.
* Realigned all file paths and naming conventions for standard web compliance.

## 🚀 Deployment
The production application is securely hosted and managed via **Neocities**, with live repository synchronization mapped through Git configurations.

### Deployment Process
1. Initialize local folder structures and verify relative mapping parameters.
2. Confirm all linked internal script paths and assets conform strictly to lowercased configurations to preserve Linux server routing compatibility.
3. Push refined codebase components into the centralized remote GitHub repository.
4. Synchronize folder updates to the live web root on Neocities.

---

## 🤝 Acknowledgments
* **Neocities Platform:** Providing accessible hosting environments for modern front-end layouts.
* **Shots.so:** Generating crisp web layout perspective mockups.
* **Google Web Fonts:** Serving high-performance typographic vectors.
* **GitHub Community:** Powering version control pipelines.

---

## 📞 Contact & License
* **Email:** [mohammed_12ali@outlook.com](mailto:mohammed_12ali@outlook.com)
* **Portfolio URL:** [https://ali-design.neocities.org](https://ali-design.neocities.org)
* **GitHub Profile:** [Md12Ali](https://github.com/Md12Ali)

*Code modifications and project content documentation are copyright © 2026 Mohammed Ali. Base framework templates and core Bootstrap libraries are released independently under standard [MIT open-source licensing parameters](https://github.com/twbs/bootstrap/blob/main/LICENSE).*
