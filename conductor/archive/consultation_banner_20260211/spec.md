# Specification: Consultation Banner Footer

## Overview
Add a high-conversion consultation banner to the bottom of every individual blog post. The banner aims to drive readers to Oleksandr Stefanovskyi's main website to schedule meetings and explore professional services.

## Functional Requirements
- **Placement:** The banner must appear at the end of the article body, before the comments section in `layouts/posts/single.html`.
- **Primary Content:**
    - An authoritative headline (e.g., "Ready to Scale Your AI Strategy?").
    - A brief call-to-action description mentioning services and testimonials.
- **Call to Action (CTA):**
    - A prominent button with the text "Schedule a Consultation".
    - The button must link to `http://stefanovskyi.com`.
- **Visual Styling:**
    - **Background:** Match the dark theme of tables/diagrams (`#1a1a1a`).
    - **Accent Color:** Use `#F1C40F` (yellow) for the primary button background and a decorative container border.
    - **Layout:** Centered or well-spaced container with clear visual separation from the post content.

## Non-Functional Requirements
- **Performance:** Ensure no external assets (beyond what's already used) are required to render the banner.
- **Mobile Responsiveness:** The banner must stack vertically or scale appropriately on smaller screens.

## Acceptance Criteria
1.  Navigate to the bottom of any blog post.
2.  The consultation banner is visible before the comments.
3.  The banner features a yellow (#F1C40F) border and a matching yellow button.
4.  Clicking the "Schedule a Consultation" button takes the user to `http://stefanovskyi.com`.
5.  The text is clearly readable against the dark background.

## Out of Scope
- Adding this banner to the homepage or the main `/posts/` archive.
- Implementing an on-site scheduling form (linking to the main site is sufficient).
