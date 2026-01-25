# AI Coding Agent Guidelines for my-website

## Project Overview
A minimal personal website project with static HTML and documentation. The repository currently contains:
- `index.html` - Main website entry point (currently empty)
- `README.md` - Project documentation
- No build system, framework, or backend dependencies

## Key Principles

### 1. Static HTML-First Approach
- No build tools or preprocessors are used (no webpack, vite, or bundlers)
- All changes should be made directly to HTML/CSS/JavaScript files
- Browser-compatible vanilla approaches preferred over frameworks
- Test functionality by opening `index.html` directly in a browser

### 2. File Structure
- Keep all website assets in the root directory or organize under logical subdirectories as needed
- Maintain simplicity—no nested build processes or complex architecture
- `index.html` serves as the landing page

### 3. Development Workflow
- Make edits directly to files—no compilation required
- Use vanilla JavaScript, plain CSS, and semantic HTML
- Test changes locally by serving files via a simple HTTP server if needed:
  ```bash
  python3 -m http.server 8000
  # or
  npx http-server
  ```

## Common Tasks & Patterns

### Adding Content to index.html
- Use semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<footer>`)
- Keep the document well-structured for accessibility
- Link external resources (CSS, JS) with relative paths

### Styling
- Create `style.css` or use `<style>` tags in `index.html` for scoped CSS
- Prefer standard CSS over inline styles for maintainability
- Test across modern browsers (Chrome, Firefox, Safari, Edge)

### Adding Interactive Features
- Use vanilla JavaScript in `<script>` tags or separate `.js` files
- Keep JavaScript minimal and focused—no heavy dependencies unless essential
- Ensure functionality works without JavaScript enabled (progressive enhancement)

## When to Add Complexity
- Only introduce build tools/frameworks if explicitly justified (e.g., SPAs, complex state management)
- Default to simplicity: vanilla HTML + CSS + JS can handle most use cases
- Document any new tooling decisions in README.md

## References
- Main entry point: [index.html](index.html)
- Project description: [README.md](README.md)
