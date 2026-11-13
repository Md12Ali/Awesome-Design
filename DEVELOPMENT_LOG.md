# Development Log — Awesome Design

This log explains what was done in each stage of the project. Many earlier commits were made through the GitHub web uploader, so they have generic messages such as "Add files via upload" or "Update README.md". This log says what those commits actually changed. The commit history has not been rewritten.

| Date | Commits (examples) | What was actually done |
|------|--------------------|------------------------|
| 27 Jan 2026 | `Initial commit`, `style.css` | Created the repository and added a first stylesheet. |
| 28 Jan 2026 | `Add files via upload`, `Create js`, `Delete Portfolio/js`, `Create delete.css`, `Create hi.css`, `Delete Portfolio/styles.css` | Uploaded the Start Bootstrap Creative and Stylish Portfolio template files and organised them into `Portfolio/css`, `Portfolio/js` and `Portfolio/img`. GitHub's web uploader cannot create empty folders, so placeholder files (`delete.css`, `hi.css`, `js.js`, `scr.js`, `delete.html`) were created to make each folder and then deleted. Removed the template's unused `assets/img` folder and `simple-line-icons.css`. |
| 28 Jan 2026 | `Fix background image path in stylish-portfolio.css` | Corrected the hero background image path. |
| 3 Feb 2026 | `README for ...`, `Add manual testing report to README`, `Add files via upload` | Wrote the first README (design process, tech stack, manual testing report and acknowledgements) and uploaded wireframe and screenshot images for it. |
| 4 Feb 2026 | `Add files via upload`, `Delete screenshot-...png`, `Replace design image in README` | Replaced the auto-named screenshots with better wireframe and mockup images, added the licence section and removed PHP and Dreamweaver badges that were not used in the project. |
| 19 May 2026 | `Rename Capture1.PNG to capture1.PNG` ... `Update index.html` | After the first feedback: started renaming images to lowercase and updated the page content and metadata. |
| 20–21 May 2026 | `Rename capture2.PNG to welfare-trust.png`, `Create custom.css`, `Fix CSS link formatting in index.html` | Gave every portfolio image a descriptive lowercase name (e.g. `welfare-trust.png`) and updated `index.html`. Created `custom.css` to hold my own styles separately from the template CSS. |
| 23 May 2026 | `Update Revised readme file.md` (many), `Add files via upload`, `Update custom.css`, `Update index.html` | Rewrote the README in stages (user stories, credits, testing), uploaded new HTML and CSS validation screenshots and wireframes, and acknowledged AI assistance. The many "Update" commits are small edits made one at a time in the GitHub editor. |
| 10 Nov 2026 | `Apply Unit 1 assessor feedback (path to pass)`, `Add live-site evidence and fix mobile navbar` | Applied the Path to Pass feedback: template attribution, moved my colour changes into `custom.css`, alt text, ARIA and `<main>`, link fixes, hero image path, mobile navbar fix and live-site screenshots. |
| 11 Nov 2026 | `Fix navigation console errors: swap jQuery slim for full build` | The slim jQuery build has no `.animate()`, so the smooth-scroll navigation threw a console error. Switched to the full jQuery 3.5.1 build. |
| 11 Nov 2026 | `Fix heading structure in Services section (H2 + H3s)` | The Services title is now an H2 and each service an H3 (previously H3 and H4s). |
| 11 Nov 2026 | `Fix text contrast in About and Services to meet WCAG AA` | Darkened the brand teal from `#1997ab` to `#0f6674` and made the About and Services text white: 6.62:1 instead of about 2.5:1. |
| 11 Nov 2026 | `Rename Portfolio directory to lowercase portfolio` | Renamed `Portfolio/` to `portfolio/` and updated all paths in the README. |
| 11 Nov 2026 | `Add development log and update README testing` | Added this log, recorded the checked colour combinations and rewrote the testing section with browsers, screen sizes, expected and actual results and bug retests. |
| 13 Nov 2026 | `Force browsers to load the updated custom.css` | Added `?v=2` to the stylesheet link because browsers were still showing the cached old colours after the redeploy. |
| 13 Nov 2026 | `Record live-site retest results in README` | Redeployed to Neocities and retested every feature at 320–1920px in Chrome, then recorded the actual results and bug retests. |

From 11 November 2026, every commit message describes the change and the reason for it.
