# James Park - Professional Site

Static professional site for James Park, focused on product management, founder-built AI SaaS work, healthcare data workflows, and regulated systems.

## Current Status

- Site is deployed to GitHub Pages at `jpark.app`.
- `index.html` is the primary portfolio surface.
- `classic.html` is a light fallback and should stay content-aligned with `index.html`.
- There is no build step.

## Features

- Cinematic primary design with a simpler classic fallback
- Fully responsive layout
- Smooth scrolling navigation
- Intersection observer animations
- Vanilla HTML, CSS, and JavaScript

## Sections

- **About**: Personal story and product operating style
- **Experience**: Craneware, Talogy, innate.ly, and earlier context
- **Featured Work**: Granite Security and Dossier
- **Tools & Tech**: Product, identity, data, delivery, AI, and compliance tags
- **Contact**: Email, LinkedIn, and GitHub

## Local Development

Open `index.html` in a browser, or run a static server if you want browser tooling to behave like production.

```sh
python3 -m http.server 8000
```

## Deployment

This site is configured for GitHub Pages. To deploy:

1. Push your changes to the repository
2. Go to repository Settings > Pages
3. Set source to "main" branch, root folder
4. Your site will be live at `https://monpip.github.io/jpark`

## Customization

### Update Your Information

Edit both `index.html` and `classic.html` when changing public positioning, experience, featured work, tools, or contact links.

### Modify Colors

Edit the CSS variables in `styles.css` and `classic.css` under `:root`.

### Add More Sections

Follow the existing section structure in `index.html` and add corresponding styles in `styles.css`.

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- No frameworks or dependencies

## License

All rights reserved.
