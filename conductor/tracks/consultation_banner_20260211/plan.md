# Implementation Plan: Consultation Banner Footer

## Phase 1: Implementation [checkpoint: 2ea9ea9]
- [x] Task: Create the `consultation_banner.html` partial (30c7223)
    - [x] Create `layouts/partials/consultation_banner.html`
    - [x] Implement HTML structure with headline and button
    - [x] Link button to `http://stefanovskyi.com`
- [x] Task: Apply styling to the banner (2ea9ea9)
    - [x] Add CSS for the banner container (background `#1a1a1a`, border `#F1C40F`)
    - [x] Style the CTA button (background `#F1C40F`, dark text)
    - [x] Ensure mobile responsiveness
- [x] Task: Integrate banner into single post layout (bedac96)
    - [x] Update `layouts/posts/single.html` to include `consultation_banner.html` before the comments partial
- [x] Task: Conductor - User Manual Verification 'Phase 1: Implementation' (Protocol in workflow.md) (2ea9ea9)

## Phase 2: Verification and Documentation
- [ ] Task: Verify rendering and functionality
    - [ ] Build the site with `hugo -D`
    - [ ] Check multiple posts to ensure banner appearance
    - [ ] Verify link and button click behavior
- [ ] Task: Update visual standards documentation
    - [ ] Update `conductor/product-guidelines.md` to include the consultation banner style
- [ ] Task: Conductor - User Manual Verification 'Phase 2: Verification and Documentation' (Protocol in workflow.md)
