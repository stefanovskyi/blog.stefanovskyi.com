# Specification: Mermaid Diagram Support

## Goal
Enable the creation and rendering of Mermaid.js diagrams directly within blog posts using a custom Hugo shortcode.

## Requirements
- Create a Hugo shortcode named `mermaid` to wrap diagram definitions.
- Integrate the Mermaid.js library (via CDN) into the site's layout.
- Ensure diagrams render correctly in both development (`hugo server`) and production builds.
- Adhere to the site's "dark" color theme for diagram styling where possible.

## Technical Approach
1. **Shortcode:** Implement `layouts/shortcodes/mermaid.html` to output a `<div class="mermaid">` containing the inner Markdown content.
2. **Layout Modification:** Override the theme's `baseof.html` or a relevant partial to include the Mermaid.js initialization script.
3. **Initialization:** Use the ESM version of Mermaid.js and initialize it with `startOnLoad: true`.
