# Awesome Design — Portfolio Website

**Live Site:** [https://ali-design.neocities.org/](https://ali-design.neocities.org/#page-top)  
**Repository:** [https://github.com/Md12Ali/Awesome-Design](https://github.com/Md12Ali/Awesome-Design)  
**Author:** Mohammed Ali  
**Unit:** Unit 1 – User Centric Front End Development (Y/650/3525)

![Portfolio Showcase Screenshot](https://github.com/Md12Ali/Awesome-Design/blob/main/Portfolio/img/101.png?raw=true)  


## 1. Project Overview
Awesome Design is a professional single-page portfolio website built to showcase my skills as a Designer and Front-End Developer to potential clients, employers, and collaborators.

The site features a clean, modern, and fully responsive layout with smooth scrolling navigation across five main sections: Hero, About, Services, Portfolio, and Contact.

## 2. UX Design

### User Stories with Acceptance Criteria

| User Story | Acceptance Criteria | Verified |
|------------|---------------------|----------|
| As a new visitor, I want to immediately understand the purpose of the site | Clear hero section with headline and call-to-action | Yes |
| As an employer, I want to see services and real projects | Dedicated Services and Portfolio sections with screenshots | Yes |
| As a mobile user, I want the site to work well on my device | Fully responsive layout using Bootstrap grid | Yes |
| As an accessibility user, I want proper support | Descriptive alt text, working links, good contrast | Yes |


  ## Core Design Principles

The design of this portfolio website is guided by key UX and UI principles to ensure clarity, accessibility, and a smooth user experience across all devices.

### 1. Simplicity
The layout avoids unnecessary complexity, focusing on clean sections, clear typography, and intuitive navigation. Users can quickly understand the purpose of the site without distractions.

### 2. Consistency
Consistent spacing, colours, typography, and iconography are used throughout the site. This creates a unified visual identity and helps users predict how elements behave.

## Accessibility

Accessibility was a key focus throughout the development of this project to ensure the website is usable by as many people as possible, including users with visual, motor, or cognitive impairments. The site follows core WCAG 2.1 AA principles and includes several features designed to improve accessibility.

### 1. Semantic HTML Structure
The website uses semantic HTML elements such as:
- `<header>`
- `<nav>`
- `<section>`
- `<main>`
- `<footer>`

This improves screen‑reader navigation and helps assistive technologies understand the structure of the page.

### 2. Alt Text for All Images
All images include descriptive `alt` attributes so users with screen readers can understand the content.  
Example: portfolio items, wireframes, and profile images all have meaningful alt descriptions.

### 3. High Contrast & Readable Typography
- Text and background colours were chosen to maintain strong contrast.
- Google Fonts (Merriweather & Merriweather Sans) provide high readability.
- Font sizes are large enough for comfortable reading on all devices.

### 4. Keyboard Navigation
The site can be navigated using only the keyboard:
- Tab order follows a logical sequence  
- Links and buttons are focusable  
- Navigation bar remains accessible on all screen sizes  

### 5. Accessible Links
- External links use `target="_blank"` with `rel="noopener"` for safety  
- Email link uses `mailto:` for direct access  
- Link text is descriptive (e.g., “View Portfolio” instead of “Click Here”)

### 6. Responsive & Mobile‑Friendly Layout
The mobile‑first design ensures:
- No horizontal scrolling  
- Touch‑friendly buttons  
- Proper spacing between interactive elements  

### 7. ARIA & Label Improvements
Where needed, ARIA attributes were added to improve clarity for assistive technologies:
- `aria-label` for navigation  
- Icons marked as decorative using `aria-hidden="true"`  

### 8. Consistent Layout & Predictable Behaviour
Users can easily predict:
- Where navigation is located  
- How sections flow  
- How buttons and links behave  

This reduces cognitive load and improves usability for all visitors.

### 9. Validation & Testing
Accessibility was checked through:
- Manual keyboard testing  
- Colour contrast checks  
- Screen‑reader friendly structure  
- HTML validation to ensure clean, error‑free markup  

The site meets the accessibility expectations for Unit 1 and provides an inclusive experience across devices.


These choices ensure the site is usable for a wide range of users, including those with visual or motor impairments.

### 4. Mobile‑First Responsiveness
The design was planned and built using a mobile‑first approach. The layout adapts seamlessly across mobile, tablet, and desktop devices using Bootstrap’s responsive grid system.

### 5. Visual Hierarchy
Content is structured using headings, spacing, and typography to guide the user’s eye. Important elements such as the hero headline, call‑to‑action buttons, and portfolio items are emphasised visually.

### 6. User Control & Clarity
Navigation is always visible, links behave predictably, and interactive elements provide visual feedback. This ensures users always know where they are and how to move through the site.

### 7. Performance & Efficiency
Images are optimised, scripts are lightweight, and the layout avoids unnecessary animations. This ensures fast loading times and smooth performance on all devices.

### 8. Purpose‑Driven Content
Every section serves a clear purpose:
- Hero: Introduce the brand  
- About: Explain who I am  
- Services: Show what I offer  
- Portfolio: Display my work  
- Contact: Provide a simple way to reach me  

## Wireframe Structure

The wireframes for this project were created during the planning phase to establish a clear visual structure before development began. They were designed in Adobe Photoshop and follow a mobile‑first approach to ensure accessibility and responsiveness across all devices.

### Purpose of the Wireframes
The wireframes were created to:
- Define the layout and hierarchy of each section
- Plan how content flows from top to bottom
- Ensure consistent spacing, alignment, and readability
- Visualise how the design adapts across desktop, tablet, and mobile
- Identify potential usability issues early in the process

### Structure Overview
Each wireframe includes the following core elements, accurately matching the three uploaded wireframes:

#### **1. Header & Navigation**
- Fixed navigation bar at the top  
- Logo positioned on the left  
- Menu links: **Home, About, Portfolio, Services, Contact**  
- Designed to collapse into a mobile menu in smaller screens  

#### **2. Hero Section**
- Large headline for immediate clarity  
- Subheading text directly underneath  
- A **“Learn More”** button (not a call‑to‑action button)  
- Clean, minimal layout to introduce the site  

#### **3. Portfolio Section**
- Prominent section title: **Portfolio**  
- Desktop wireframe: **8 portfolio items** arranged in two rows  
- Tablet wireframe: **4 portfolio items**  
- Mobile wireframe: **3 portfolio items**  
- Consistent placeholder boxes labelled “Portfolio Item”  
- Designed for hover or click interaction in the final build  

#### **4. About Section**
- Two‑column layout  
  - Left: Profile image placeholder  
  - Right: “About Me Text” block  
- Additional horizontal bars representing supporting text or skills  
- Clear introduction to the creator  

#### **5. Services Section**
- Three service blocks displayed horizontally  
- Each block includes:
  - A user icon  
  - A service title (Service One, Service Two, Service Three)  
- Tablet and mobile versions stack vertically for readability  

#### **6. Contact Section**
- Simple, accessible layout  
- Email address displayed clearly  
- Social media icons included (Twitter, Facebook, Email)  
- Designed for quick communication  

#### **7. Footer**
- Clean footer containing:  
  **© Mohammed Ali – Awesome Design**  
- Consistent across all wireframe versions  

### Wireframe Goals
The wireframes were designed to meet the following goals:
- Ensure navigation remains visible and accessible  
- Present portfolio items clearly and professionally  
- Provide a clean, simple contact method  
- Maintain consistent structure across desktop, tablet, and mobile  
- Support a smooth user journey from introduction → portfolio → contact  

### Wireframe Images
Below are the final low‑fidelity wireframes used during development:

### Homepage Wireframe
![Home Wireframe](Portfolio/img/home%20wireframe.jpeg)

*Alt: Low‑fidelity wireframe showing hero banner, navigation, about, services, portfolio, and contact layout.*

### Portfolio Wireframe
![Service Wireframe](Portfolio/img/service%20wireframe.jpeg)

*Alt: Wireframe showing responsive grid layout for project thumbnails.*

### Contact Section Wireframe
![Contact Wireframe](Portfolio/img/contact%20wireframe.jpeg)

*Alt: Wireframe showing simple contact block with email link.*

### Wireframe Acceptance Criteria
- Layout must remain consistent across desktop, tablet, and mobile.
- Navigation must remain visible and accessible.
- Portfolio images must display clearly with hover or click interaction.
- Contact section must provide clear communication options.

## 3. Features
- Fixed navbar with hamburger menu and smooth anchor scrolling
- Hero section with strong value proposition
- About section highlighting professional background
- Responsive services grid with icons
- Interactive portfolio gallery with lightbox effect
- Contact section with working email and phone links
- Hover effects and professional visual feedback

### **Existing Features**
- Responsive navigation bar  
- Hero section with call‑to‑action  
- Portfolio gallery  
- About section  
- Services section  
- Contact section with working email link  
- Footer with copyright  
- Fully responsive layout  
- External links opening in new tabs  
- All images renamed to lowercase  
- All images include descriptive alt text  

### **Future Features**
- Dark mode  
- Interactive gallery  
- Contact form with validation  



## 4. Technologies Used
- **HTML5** – Semantic markup
- **CSS3** – Custom styles and overrides
- **Framework:** Bootstrap 4.5.3 (grid system, navbar, responsiveness)
- **Typography:** Google Fonts – Merriweather and Merriweather Sans
- **Icons:** Font Awesome 5.15.1
- **Interactivity:** jQuery, Magnific Popup
- **Tools:** Adobe Photoshop & Illustrator, Git/GitHub, Neocities

## 5. Credits & Attribution
This project was built by **customising two Start Bootstrap templates**. Using templates is normal and acceptable in web development.

### Templates Used
- **Start Bootstrap – Creative v6.0.4** (MIT License) – Core structure, masthead, navigation, `styles.css`, and `scripts.js`
- **Start Bootstrap – Stylish Portfolio v5.0.9** (MIT License) – Portfolio and services styling (`stylish-portfolio.css`)

### What I Customised (My Own Work)
- All personal text content (About, Services, Contact)
- Portfolio gallery with my own project screenshots
- Custom logo design and integration
- Colour scheme adjustments to match my branding
- Accessibility improvements (alt text, mailto links, `target="_blank"`)
- File renaming to lowercase with descriptive names
- Custom CSS overrides in `css/custom.css`
- Full documentation and testing

**External Resources:** Bootstrap 4.5.3, Google Fonts, Font Awesome, Magnific Popup.

### AI Assistance Acknowledgement
Parts of this project’s documentation were supported by Microsoft Copilot, which assisted with:
- README structuring and clarity improvements
- Grammar and formatting corrections
- Accessibility and validation guidance
- General development support

All design decisions, code implementation, customisations, and final content were created and approved by me.


## 6. Testing
**Validation Evidence:**
- HTML passes W3C Validator → [![HTML Validation](Portfolio/img/html-validation.jpeg)](Portfolio/img/html-validation.jpeg)

- Alt: Screenshot showing W3C HTML validation with no errors.
- CSS passes Jigsaw Validator → [![CSS Validation](Portfolio/img/css-validation.jpeg)](Portfolio/img/css-validation.jpeg)

- Alt: Screenshot showing Jigsaw CSS validation with no errors.

**Manual Testing Summary:**

### **Manual Testing Table**

| Feature | Test | Expected Result | Actual Result | Pass |
|--------|------|----------------|----------------|------|
| Navigation links | Click each link | Smooth scroll to section | Works correctly | ✔ |
| External links | Click GitHub/Neocities | Opens in new tab | Works | ✔ |
| Email link | Click email | Opens mail client | Works | ✔ |
| Images | Load on all devices | Display correctly | Works | ✔ |
| Responsiveness | Resize browser | Layout adjusts | Works | ✔ |
| Alt text | Inspect images | Alt text present | All correct | ✔ |

### **Device Testing**
- iPhone 12  
- Samsung Galaxy S21  
- iPad 10th Gen  
- Windows laptop  
- MacBook Air  

### **Browser Testing**
- Chrome  
- Firefox  
- Safari  
- Edge

### Acknowledgments
I would like to express my sincere gratitude to my assessor, Yassin Hassan, for the constructive feedback and clear guidance provided during the assessment process. These insights were instrumental in helping me improve the accessibility, documentation, and technical compliance of this portfolio.

I also acknowledge the Start Bootstrap team for their high-quality, open-source templates, which provided the foundational structure for this project, and the broader web development community for the documentation that supported my learning journey.

## 7. Bugs Fixed
| Bug                          | Fix Applied                     | Status |
|-----------------------------|---------------------------------|--------|
| Navbar overlap on mobile    | CSS media queries               | Fixed  |
| Broken email link           | Added `mailto:` prefix          | Fixed  |
| Capitalised image filenames | Renamed to lowercase            | Fixed  |

## 8 Deployment Process

The website is deployed using **Neocities**, a free static hosting platform suitable for HTML, CSS, JavaScript, and image-based projects. The deployment process ensures that the live version of the site matches the GitHub repository exactly, as required by the Unit 1 assessment criteria.

### 1. Preparing the Project
Before deployment, the following steps were completed:
- All files were organised into a clear folder structure (`Portfolio/`, `img/`, `css/`, `js/`)
- Image filenames were converted to lowercase for consistency
- HTML and CSS were validated using W3C validators
- All links, navigation anchors, and file paths were tested locally

### 2. Uploading to Neocities
The site was deployed using the following steps:

1. Created a Neocities account  
2. Logged into the Neocities dashboard  
3. Uploaded the entire project folder, including:  
   - `index.html`  
   - `css/` folder  
   - `js/` folder  
   - `img/` folder  
   - `Portfolio/` folder  
4. Ensured all files and subfolders matched the GitHub structure  


### 3. Updating the Live Site
Whenever changes are made:
1. Files are updated in GitHub  
2. The same updated files are re-uploaded to Neocities  
3. The live site is refreshed to confirm the update  
4. A final check is performed to ensure no broken links or missing assets

### 4. Verification (Path‑to‑Pass Requirement)
After deployment, the following checks were completed:
- The live Neocities version matches the GitHub repository exactly  
- All images load correctly  
- Navigation links work on desktop and mobile  
- External links open in new tabs  
- Email link functions correctly  
- Portfolio items display as intended  
- No console errors appear in the browser  

### 5. Live Deployment Link
The final deployed website can be viewed at:  
**https://ali-design.neocities.org/**

## 9. How to Run Locally

1. Clone the repository  
2. Open `index.html` in any browser  
3. No installation required  

---

## 10. Contact

**Mohammed Ali**  
Email: **mohammed_12ali@outlook.com**
