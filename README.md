# KoNote2 Website

Marketing and documentation website for [KoNote2](https://github.com/gilliankerr/KoNote-Redux), an open source participant outcome management system for nonprofits.

## Structure

```
konote-website/
├── index.html           # Home page
├── features.html        # What KoNote2 does and doesn't do
├── getting-started.html # Evaluation and deployment guide
├── documentation.html   # Links to full documentation
├── security.html        # Security features and responsibilities
├── services.html        # Professional setup services
├── faq.html            # Frequently asked questions
├── css/
│   └── style.css       # Stylesheet
└── images/             # Screenshots (to be added)
```

## Hosting

This site is designed for GitHub Pages. Enable Pages in repository settings, pointing to the main branch.

## Local Development

Open `index.html` in a browser. No build step required.

## Adding Screenshots

1. Add images to the `images/` folder
2. Replace the placeholder `<div class="screenshot-placeholder">` elements with `<img>` tags
3. Include descriptive `alt` text for accessibility

## Customisation

- **Contact email**: Update `your-email@example.com` in `services.html`
- **GitHub links**: Update repository URLs in footer if the repo location changes
- **Colours**: Edit CSS custom properties in `css/style.css`

## Licence

This website is released under the MIT Licence, same as KoNote2 itself.
