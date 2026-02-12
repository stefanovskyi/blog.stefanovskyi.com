# Implementation Plan: Consultation Banner Footer

## Phase 1: Implementation
- [x] Task: Create the `consultation_banner.html` partial (30c7223)
    - [ ] Create `layouts/partials/consultation_banner.html`
    - [ ] Implement HTML structure with headline and button
    - [ ] Link button to `http://stefanovskyi.com`
- [x] Task: Apply styling to the banner (1d4b891)
    - [ ] Add CSS for the banner container (background `#1a1a1a`, border `#F1C40F`)
    - [ ] Style the CTA button (background `#F1C40F`, dark text)
    - [ ] Ensure mobile responsiveness
- [ ] Task: Integrate banner into single post layout
    - [ ] Update `layouts/posts/single.html` to include `consultation_banner.html` before the comments partial
- [ ] Task: Conductor - User Manual Verification 'Phase 1: Implementation' (Protocol in workflow.md)

## Phase 2: Verification and Documentation
- [ ] Task: Verify rendering and functionality
    - [ ] Build the site with `hugo -D`
    - [ ] Check multiple posts to ensure banner appearance
    - [ ] Verify link and button click behavior
- [ ] Task: Update visual standards documentation
    - [ ] Update `conductor/product-guidelines.md` to include the consultation banner style
- [ ] Task: Conductor - User Manual Verification 'Phase 2: Verification and Documentation' (Protocol in workflow.md)
