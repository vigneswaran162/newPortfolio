# Vigneswaran – Full Stack Developer Portfolio

A static, dependency-free portfolio built with **HTML5, CSS3 and vanilla JavaScript** only.

## Structure

```
newPortfolio/
├── index.html          # Semantic markup + SEO metadata
├── css/style.css       # Design tokens (CSS variables), components, responsive rules
├── js/script.js        # Loader, reveal/typing/counter animations, nav, form
├── ASSETS/             # Images and resume PDF (unchanged location)
└── README.md
```

## Run locally

Open `index.html` in a browser, or serve the folder (e.g. `npx serve .` / VS Code Live Server).

## Customising

- Colours/fonts/radius: edit the `:root` variables at the top of `css/style.css`.
- Typing roles: `roles` array in `startTyping()` in `js/script.js`.
- Contact form uses `mailto:` (no backend). Change `CONTACT_EMAIL` in `js/script.js`.
- Add a project: copy an `<article class="project ...">` block in `index.html`.

External resources: Google Fonts (Inter, Space Grotesk) and icons8 skill icons only.
