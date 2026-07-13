# Personal Portfolio — Arvin Carl Simon Urayan

A responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript.

## Live Preview

Open `index.html` in a browser, or deploy to any static hosting (GitHub Pages, Vercel, Netlify).

## Features

- **Sticky navbar** with hamburger menu on mobile
- **Hero / Profile** section with profile photo and resume download link
- **Projects** section showcasing featured work
- **Skills** section with beginner / learning / familiar proficiency badges
- **Certificates** section with direct links to credential files
- **Currently Learning** section highlighting active study goals
- **Contact** section with social links and a working email form (EmailJS)
- Scroll-to-top button
- Toast notifications for form submission feedback
- Fully responsive — works on mobile, tablet, and desktop

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Scripting | JavaScript |
| Email | [EmailJS](https://www.emailjs.com/) |
| Icons | [Font Awesome 6](https://fontawesome.com/) · [Devicons](https://devicons.dev/) |
| Fonts | Google Fonts — Inter, Poppins |

## Project Structure

```
Portfolio/
├── index.html      # Main HTML file
├── style.css       # All styles and responsive breakpoints
├── script.js       # Navbar toggle, contact form, scroll-to-top
├── config.js       # EmailJS keys (excluded from version control)
├── README.md
└── public/
    ├── profile.png
    └── favicon.png
```

## Setup

1. Clone or download the repository.
2. Add your EmailJS credentials to `config.js`:

   ```js
   const EMAILJS_CONFIG = {
     publicKey: "YOUR_PUBLIC_KEY",
     serviceId: "YOUR_SERVICE_ID",
     templateId: "YOUR_TEMPLATE_ID",
   };
   ```

3. Open `index.html` in a browser — no build step required.

## Responsive Breakpoints

| Breakpoint | Layout changes |
|-----------|----------------|
| `≤ 768px` | Hamburger menu, single-column sections, reduced padding |
| `≤ 480px` | Smaller headings, smaller profile photo, 16px gutter |

## License

© 2026 Arvin Carl Simon Urayan. All rights reserved.
