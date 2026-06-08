# Gokul Krishna — Personal Portfolio

My personal developer portfolio, hosted on [GitHub Pages](https://gokul0krishna.github.io).

## Setup

1. Install dependencies:

```bash
npm install
```

2. Run the development server:

```bash
npm start
```

3. Open the site at `http://localhost:1234`

## Build

```bash
npm run build
```

## Customization

- **Content**: Edit `src/index.html` — all sections have `<!-- TODO: ... -->` comments marking where to add your info.
- **Images**: Replace files in `src/assets/` (profile photo, project screenshots, favicon, resume PDF).
- **Colors**: Edit `src/sass/abstracts/_variables.scss` to change the color scheme.
- **Styles**: Modify Sass partials in `src/sass/` for deeper customization.

## Project Structure

```
src/
├── index.html          — Main page markup
├── index.js            — ScrollReveal & tilt animation entry point
├── styles.scss         — Top-level Sass file
├── assets/             — Images, icons, resume PDF
├── data/               — ScrollReveal config
├── scripts/            — Animation scripts
└── sass/               — Sass partials (variables, sections, components)
```

## Deployment

Pushes to `main` automatically build and deploy to GitHub Pages via the `.github/workflows/gh-pages.yml` workflow.

## Technologies

- [Parcel](https://parceljs.org/) — Bundler
- [Bootstrap 5](https://getbootstrap.com/) — Frontend framework
- [Sass](https://sass-lang.com/) — CSS preprocessor
- [ScrollReveal](https://scrollrevealjs.org/) — Scroll animations
- [Vanilla Tilt](https://micku7zu.github.io/vanilla-tilt.js/) — Parallax tilt effect

## License

MIT — see [LICENSE.md](LICENSE.md)
