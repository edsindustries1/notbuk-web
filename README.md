# Not Buk — marketing website

Static site (plain HTML/CSS, no build step) for the Not Buk iOS app: landing page (`index.html`), support/FAQ (`support.html`), and privacy policy (`privacy.html`), with shared styles in `styles.css`.

## Publishing on GitHub Pages

Push this `website/` directory to a GitHub repository (either as the repo root, or point Pages at a `/docs` folder or a dedicated branch), then open the repo's **Settings > Pages**, choose the branch/folder containing these files as the source, and save — GitHub serves the site at `https://<username>.github.io/<repo>/` within a minute or two. No build configuration is needed since everything is plain HTML and CSS.

**TODO before launch:** the "Download on the App Store" button on `index.html` currently links to `#`. Once the app is live, replace it with the real App Store URL and, ideally, Apple's official App Store badge artwork (see the `TODO` comment in `index.html`).
