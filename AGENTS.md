## Cursor Cloud specific instructions

This is a static personal landing page (single `index.html` with inline CSS/SVG). No build tools, package managers, or external dependencies.

### Running locally

```
python3 -m http.server 8080 --directory /workspace
```

Then open `http://localhost:8080/` in a browser.

### Notes

- No linting, testing frameworks, or build steps exist in this repo.
- The site is deployed via GitHub Pages with a custom domain (`emanuelg.dev`) configured in the `CNAME` file.
- Any static HTTP server works for local development (Python, Node `npx serve`, etc.).
