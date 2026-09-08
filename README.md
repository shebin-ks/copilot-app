# Codify

Codify is a lightweight, responsive landing page demo built with React 18. It uses React components and client-side state for navigation while keeping the project deliberately small: there is no bundler, package manager, or build step.

## Pages

- **Home** - hero section and feature highlights
- **About** - project mission and technology overview
- **Services** - design systems, performance, and consulting offerings
- **Docs** - quick-start information
- **Contact** - contact details and collaboration prompt

## Run locally

Open `index.html` directly in a browser, or serve the folder with a static server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Project structure

- `index.html` - application markup, React components, and page state
- `styles.css` - responsive layout, colors, typography, and component styles

React, ReactDOM, and Babel are loaded from the unpkg CDN at runtime. An internet connection is required when loading the page unless those dependencies are vendored locally.
