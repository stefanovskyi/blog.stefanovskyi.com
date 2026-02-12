# Implementation Plan: Individual Post Page Header

## Phase 1: Implementation [checkpoint: f8d5cee]
- [x] Task: Create the `post_header.html` partial (4cf064b)
    - [x] Create `layouts/partials/post_header.html`
    - [x] Implement logo, title, and "All posts" link logic
    - [x] Ensure links point to `/posts`
    - [x] Apply green color (#2bbc8a) to the "All posts" link
- [x] Task: Integrate header into single post layout (34c6d36)
    - [x] Update `layouts/posts/single.html` to include `post_header.html` above `page_nav.html`
- [x] Task: Conductor - User Manual Verification 'Phase 1: Implementation' (Protocol in workflow.md) (f8d5cee)

## Phase 2: Verification and Cleanup
- [ ] Task: Verify functionality and styling
    - [ ] Build the site with `hugo -D`
    - [ ] Verify HTML output for correct links and structure
    - [ ] Confirm mobile responsiveness matches theme expectations
- [ ] Task: Conductor - User Manual Verification 'Phase 2: Verification and Cleanup' (Protocol in workflow.md)
