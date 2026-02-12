# Implementation Plan: Individual Post Page Header

## Phase 1: Implementation
- [x] Task: Create the `post_header.html` partial (4cf064b)
    - [ ] Create `layouts/partials/post_header.html`
    - [ ] Implement logo, title, and "All posts" link logic
    - [ ] Ensure links point to `/posts`
    - [ ] Apply green color (#2bbc8a) to the "All posts" link
- [ ] Task: Integrate header into single post layout
    - [ ] Update `layouts/posts/single.html` to include `post_header.html` above `page_nav.html`
- [ ] Task: Conductor - User Manual Verification 'Phase 1: Implementation' (Protocol in workflow.md)

## Phase 2: Verification and Cleanup
- [ ] Task: Verify functionality and styling
    - [ ] Build the site with `hugo -D`
    - [ ] Verify HTML output for correct links and structure
    - [ ] Confirm mobile responsiveness matches theme expectations
- [ ] Task: Conductor - User Manual Verification 'Phase 2: Verification and Cleanup' (Protocol in workflow.md)
