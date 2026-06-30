# CRW Race-Craft Studios 
A responsive, multi-page static website built for **CRW Race-Craft Studios**, Singapore's first local CNC motorcycle racing brand. The site showcases precision-engineered, track-validated motorcycle hardware like Paddock Spools and Apex Oil Caps, alongside a custom bulk-order enquiry system.

##  Features

* **Multi-Page Architecture:** Includes a Home page, Product Detail pages (Spools & Oil Caps), and a Custom Services page.
* **Fully Responsive Design:** Custom CSS utilizing Flexbox and Grid, with breakpoints optimized for desktop, tablet, and mobile viewing.
* **Scroll Animations:** Integrated with [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) for smooth, cinematic element reveals.
* **Dynamic Contact Form:** A vanilla JavaScript-powered enquiry form on the Services page that pre-fills the user's default email client.
* **Modern UI/UX:** Dark-mode aesthetic with brand-specific gold and red accents, sticky headers, and hover-triggered dropdown navigation.

##  Tech Stack

* **HTML5:** Semantic markup and meta tags optimized for basic SEO and social sharing (Open Graph).
* **CSS3:** Custom properties (variables) for easy theming, CSS Grid/Flexbox layouts, and media queries.
* **JavaScript (Vanilla):** Handles form data extraction and Mailto link generation.
* **Third-Party Libraries:** AOS.js for scroll animations.

##  Project Structure

```text
├── assets/             # Images, logos, and video files (e.g., crwlogo.png, animation.mp4)
├── css/
│   └── style.css       # Core stylesheet containing all styling and media queries
├── index.html          # Homepage / Brand Introduction
├── bobbypins.html      # Product Page: Paddock Spools
├── oilcaps.html        # Product Page: Apex Oil Caps
├── services.html       # Services & Custom Enquiry Form
└── README.md           # Project documentation
