Platform 9 Chai

A responsive static landing page for a fictional Mumbai chai stall, themed on local train station signage. Built with semantic HTML5 and plain CSS as the Week 1 task of the Yuva Intern frontend web development internship (transforming wireframes into static web pages).

Preview

Open index.html in any modern browser. No build step or dependencies are needed.

Features
Semantic structure using header, nav, main, section, article, aside, address and footer
Departure-board style menu built as an accessible HTML table
"How it works" steps drawn as a train route line, which turns vertical on mobile
Responsive layout using CSS Grid, Flexbox, fluid type with clamp() and media queries at 900px and 600px
Theme controlled by CSS custom properties (colours, fonts, radius)
Visible keyboard focus styles and prefers-reduced-motion support
Project structure
platform9-chai/
├── index.html    # Page structure and content
├── styles.css    # Tokens, base, components, responsive rules
└── README.md

Layout strategy

The wireframe's main blocks (header, navigation, hero, content areas, footer) map directly to semantic elements. Each section is a CSS Grid container that collapses to a single column on tablets and phones.

Challenges and solutions
Route line on mobile: repositioned the pseudo-elements to a vertical line inside the 600px media query.
Table overflow on small screens: wrapped the table in a container with overflow-x: auto.
Conflicting spacing rules: kept selectors simple and consistent to avoid specificity clashes.
Testing

Checked in Chrome DevTools at 375px (mobile), 768px (tablet) and 1280px (desktop).

Possible improvements
Mobile menu toggle
Image gallery section
Pixel-comparison against the wireframe with an overlay tool

Author
Prashansa Raut | Frontend Web Developer Intern, Yuva Intern
