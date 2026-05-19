# Awesome Design — Professional Portfolio Website

## 1. Project Overview
**Awesome Design** is an interactive, responsive single-page portfolio website built to showcase my web design capabilities and front-end development proficiency. The application acts as a clean, highly accessible digital footprint engineered to provide prospective clients, tech recruiters, and hiring managers immediate insight into my professional background, core technical skills, and creative project workflow.

- **Live Deployment URL:** [https://ali-design.neocities.org/](https://ali-design.neocities.org/)
- **GitHub Repository:** [https://github.com/Md12Ali/Awesome-Design](https://github.com/Md12Ali/Awesome-Design)

---

## 2. UX Design & Development Documentation

### 2.1 The Five Planes of UX
1. **Strategy:** Solves the core user demand for a unified portfolio platform where digital recruiters and local businesses can instantly vet technical design credentials, review project case studies, and initiate zero-friction contact.
2. **Scope:** Delivers a performant single-page architecture featuring a high-impact Hero welcome, a structured Professional Bio, an interactive Services grid, an accessible Portfolio project display, and an optimized Contact portal.
3. **Structure:** Establishes a seamless, linear information hierarchy that flows logically from introducing professional credentials down to rendering visual proof of competency (past works) and processing actionable user intent (direct communication).
4. **Skeleton:** Implements a sticky main navigation matrix that maintains persistent navigation utility across mobile, tablet, and desktop viewports, minimizing excessive scrolling loops.
5. **Surface:** Applies optimized typographic contrast, clean semantic container lines, and responsive accent variations to focus visitor attention directly onto core portfolio products.

### 2.2 User Stories with Acceptance Criteria & Verification Evidence

#### User Story 1: The First-Time Desktop Recruiter
* **User Statement:** As a first-time visitor, I want the site's primary purpose and the developer's creative specialties to be immediately obvious without scrolling through walls of text, so that I can quickly gauge if they meet my hiring profile.
* **Acceptance Criteria:**
  - The hero masthead must display a distinct, high-impact professional headline above the fold.
  - Core services must be cleanly structuralized using recognizable visual iconography.
* **Verification / Evidence:** The hero landing section displays the explicit branding declaration *"I am a designer & Front-end developer"*, followed by an itemized services panel separating layout configurations, branding, and development tasks.

#### User Story 2: The Mobile Evaluator
* **User Statement:** As a tech recruiter evaluating portfolios on a smartphone, I want a fully fluid, adaptive layout that scales perfectly across small displays without horizontal breaking, so that I can inspect code quality cleanly on the move.
* **Acceptance Criteria:**
  - Standard multi-column grid arrays must dynamically stack cleanly into unified vertical structures on small viewports.
  - Persistent wide link menus must gracefully fold into an interactive, touch-accessible mobile hamburger interface.
* **Verification / Evidence:** Fluid Bootstrap container rules prevent layout overflow on low-resolution Viewports. The top navigation bar automatically collapses into an off-canvas responsive menu on mobile viewports.

#### User Story 3: The Prospective Client Auditing Code Proof
* **User Statement:** As a freelance client, I want to review visual case studies of past work directly on the portfolio page with interactive feedback, so that I can judge the engineer's aesthetic design capabilities.
* **Acceptance Criteria:**
  - The portfolio segment must display explicit project screenshots built with interactive visual hover cues.
  - Image assets must be integrated with lightbox pop-up behaviors to permit deep visual auditing without forced page refreshes.
* **Verification / Evidence:** A clean 6-item portfolio matrix utilizes dynamic CSS hover text transformations and integrates the Magnific Popup library to launch instantaneous image overlays.

#### User Story 4: The Urgent Hiring Manager
* **User Statement:** As a busy hiring manager, I want to initiate direct communication or review remote code source repositories instantly via separate instances without losing my active place on the portfolio site.
* **Acceptance Criteria:**
  - The contact node must provide a fully operational automated communication trigger (`mailto:` protocol).
  - External links routing to remote domains (such as GitHub) must execute within isolated browser tabs (`target="_blank"` configuration).
* **Verification / Evidence:** The primary communication action points utilize explicit mail routing definitions, and all outside target hyperlinks are bound to safe, new browser tab routing instances.

### 2.3 Visual Planning & Layout Blueprints
- **Desktop Grid Blueprint (`img/scratch.png`):** Formulates the horizontal layout flow, establishing column structures, typography boundaries, and section block alternating constraints.
- **Mobile Adaptive Strategy (`img/w.png` / `img/w3.png`):** Outlines vertical element stacking behavior, element downscaling, and touch target scaling rules for smaller device classes.

---

## 3. Core Features
- **Smooth-Scrolling Sticky Navigation:** Track-aware navigation bar that remains locked to the viewport header on desktop environments and converts seamlessly into an interactive toggle menu on mobile screens.
- **Dynamic Lightbox Image Component:** Built-in modal engine allowing reviewers to expand and view high-resolution interface images without leaving the parent environment.
- **Micro-Interaction Hover States:** Specialized CSS hover matrices across all portfolio card links to deliver crisp visual feedback upon user cursor entry.
- **Accessibility Infrastructure Mastery:** Explicit, meaningful descriptions embedded inside alternative attributes across all image node targets ensuring flawless screen-reader operation.
- **Isolated Target Redirection:** Structured out-of-bounds link mapping that preserves site state by anchoring third-party assets inside separated browser viewports.

---

## 4. Technologies & Libraries Used
- **Structural Foundation:** HTML5 (Strict Semantic Architecture)
- **Styling Layer:** CSS3 (Custom Responsive Media Refinements & Structural Overrides)
- **Responsive Framework:** Bootstrap v4.5.3 (Fluid Layouts & Grid Mechanics)
- **Typography Systems:** Google Fonts Web Integration — **Merriweather** & **Merriweather Sans**
- **Icon Packages:** Font Awesome v5.15.1 & Simple Line Icons
- **Scripting Engines & Libraries:** JavaScript (ECMAScript 6), jQuery v3.5.1, and Magnific Popup (Lightbox Modal System)

---

## 5. Credits, Attribution & Customization Log

### 5.1 Open-Source Scaffolding & Templates Used
To construct a highly reliable, cross-browser responsive architecture, this project leverages open-source foundations under the official terms of the MIT License. Baseline code wireframing and structure was adapted from:
- **Start Bootstrap — Creative v6.0.4** (Underlying framework foundation, `css/styles.css`, and core `js/scripts.js` behaviors): Utilized to set up the baseline layout container matrix, header section, and portfolio responsive asset block framework.
- **Start Bootstrap — Stylish Portfolio v5.0.9** (`css/stylish-portfolio.css` mechanics): Select layout values and off-canvas slide-out tracking components were evaluated and integrated into the layout.

### 5.2 Deep Technical Customizations & Original Enhancements
While built on open-source foundations, the underlying template files were heavily refactored, extended, and customized to align with unique technical criteria and design rules:
1. **Complete Content Transformation:** Stripped out all template placeholder configurations, text blocks, and mock data. Authored and structured personalized copy for the About bio, operational service matrices, and detailed case studies.
2. **Typography Architecture Overhaul:** Fully purged the default template typography packages (Montserrat, Open Sans, etc.) from the underlying stylesheets. Engineered a fresh typographical scale powered by *Merriweather* and *Merriweather Sans* to match professional web layout guidelines.
3. **Asset & Photographic Re-engineering:** Swapped all generic template background assets and theme vectors with authentic work samples, custom branding graphics, and highly compressed web-optimized layout screenshots.
4. **Accessibility Properties Integration:** Fixed structural omissions in the base boilerplate codes by inserting explicit, rich descriptive captions across all empty alternative tags (`alt="..."`), successfully achieving strict web accessibility validation compliance.
5. **Hyperlink Strategy & Protocol Resolution:** Remedied invalid layout connection routes, corrected dead interaction handles by setting up structural communication layer rules (`mailto:` protocol mapping), and applied strict sandboxing targets (`target="_blank"` with `rel="noopener"`) across all outer hyperlinks.
6. **Code Maintenance & Script Optimizations:** Cleaned up overlapping reference links, removed duplicate third-party library script injections, and streamlined class rules to minimize system resource calls.

### 5.3 Auxiliary Tools
- **AI Development Copilots:** Gemini AI used for document review, code quality optimization, and formal testing matrix construction.
- **Design Applications:** Adobe Creative Suite (Photoshop/Illustrator) used for editing custom project assets, processing image scales, and export compilation.

---

## 6. Testing, Code Validation & Bug Log

### 6.1 Automated Code Compliance Verification
To guarantee adherence to modern web criteria and ensure cross-browser parsing stability, the live application was processed through automated validation checks:

1. **W3C Nu HTML Validation Service:**
   - **Status:** 100% Pass. Checked via URL routing. All structural layout codes, semantic mappings, and attributes validated with zero errors.
   - **Evidence Tag:** ![HTML Validation Success](img/html-validation.png)

2. **W3C Jigsaw CSS Validation Engine:**
   - **Status:** 100% Pass. Checked style document sheets. Verified all custom styling classes, framework overrides, and responsive breakpoints with zero styling failures.
   - **Evidence Tag:** ![CSS Validation Success](img/css-validation.png)

### 6.2 Manual Functional Validation Testing Matrix
A deep manual testing cycle was deployed across various operating system environments and browsers (Chrome, Safari, Edge, Firefox) to ensure zero failures across interactive assets:

| Test ID | Section / Context | Action Triggered | Expected Operational Outcome | Final Status |
| :--- | :--- | :--- | :--- | :---: |
| **TC-NAV-01** | Global Navigation | Click "About" link in top navbar | Viewport smoothly transitions down to the professional bio section | **PASS** |
| **TC-NAV-02** | Global Navigation | Click "Services" link in top navbar | Viewport smoothly transitions down to the specialization asset grid | **PASS** |
| **TC-NAV-03** | Global Navigation | Click "Portfolio" link in top navbar | Viewport smoothly transitions down to the custom work showcase cards | **PASS** |
| **TC-NAV-04** | Global Navigation | Click "Contact" link in top navbar | Viewport smoothly transitions down to the communication endpoints | **PASS** |
| **TC-MOB-05** | Mobile Viewports | Tap mobile menu button overlay | Responsive navigation panel instantly drops down without layout drift | **PASS** |
| **TC-PORT-06** | Portfolio Matrix | Click a project screenshot thumbnail | Launches fluid Magnific Popup lightbox overlay containing scaled views | **PASS** |
| **TC-CONT-07** | Contact Action | Click email hypertext link | Automatically triggers local device mail user client, pre-addressed | **PASS** |
| **TC-EXT-08** | Outer Boundaries | Click external GitHub repository link | Opens remote code target cleanly inside a separate, secure browser tab | **PASS** |

### 6.3 Isolated Defect Remediation Log
During the assembly cycle, three functional bugs were detected, tracked down, and permanently repaired:
- **Bug Fix 1: Horizontal Component Grid Collision**
  * *Description:* Custom string lengths caused text content within navigation boundaries to collide and overlap adjacent text on specific mid-range viewports.
  * *Resolution:* Altered relative padding settings and inserted clear media boundary breakpoints within custom styling code sheets to protect element spacing.
- **Bug Fix 2: Session Hijacking via External Routing Links**
  * *Description:* Early hyperlinks lacked tab separation parameters, pushing users away from the live application and breaking active session history states.
  * *Resolution:* Refactored external anchor links to execute on separate tabs using explicitly configured `target="_blank"` and security-compliant `rel="noopener"` parameters.
- **Bug Fix 3: Dead Form Interaction Handler Route**
  * *Description:* Clicking the contact anchor triggered a site page 404 error instead of initializing a local message dispatch box.
  * *Resolution:* Patched the markup source code to place the mandatory missing electronic transport prefix protocol string (`mailto:`) directly before the email address value.

---

## 7. Deployment Logistics

The production application is compiled and hosted live on cloud servers via **Neocities**.

### Steps for Local Deployment & Cloning:
1. **Clone the Version Workspace:**
   ```bash
   git clone [https://github.com/Md12Ali/Awesome-Design.git](https://github.com/Md12Ali/Awesome-Design.git)
   cd Awesome-Design
