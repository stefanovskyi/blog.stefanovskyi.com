# Specification: Individual Post Page Header

## Overview
Enhance the user experience on individual blog post pages by adding a persistent header that provides clear navigation back to the full list of posts. This header should mimic the style and branding found on the `/posts` (archive) page.

## Functional Requirements
- **Header Placement:** The header must be inserted at the top of the individual post page (`layouts/posts/single.html`), specifically above the existing `page_nav.html` partial.
- **Branding Elements:**
    - Display the site logo/avatar (using the same logic as `header.html`).
    - Display the site title (`.Site.Title`).
- **Navigation Links:**
    - The site logo and title must link to the `/posts` page.
    - An "All posts" link must be displayed below the title, also linking to the `/posts` page.
- **Color Accent:** The "All posts" link should use the project's primary green accent color (`#2bbc8a`).

## Non-Functional Requirements
- **Styling Consistency:** The header's layout, fonts, and spacing must match the existing `header.html` used on other pages of the site.
- **Mobile Responsiveness:** The header must adhere to the theme's responsive breakpoints and behavior (defined in `header.scss`).

## Acceptance Criteria
1.  Navigate to any individual blog post.
2.  The header with the logo, title, and "All posts" link is visible at the top of the page.
3.  Clicking the logo, title, or "All posts" link takes the user to `https://blog.stefanovskyi.com/posts`.
4.  The "All posts" link is styled in green (#2bbc8a).
5.  On mobile devices, the header scales or collapses according to the theme's standard behavior.

## Out of Scope
- Modifying the header on the homepage or the main `/posts` list page.
- Adding additional social links or search functionality to this specific header.
