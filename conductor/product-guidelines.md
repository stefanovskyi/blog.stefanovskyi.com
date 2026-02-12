# Product Guidelines

## Content Tone & Voice
- **Authoritative & Trustworthy:** Use professional, experience-led language to build authority with senior engineering leaders and CTOs.
- **Pragmatic & Plain-spoken:** Bridge the gap between technical complexity and business value by using direct, jargon-free explanations where possible.

## Content Presentation
- **Strategic Impact First:** Lead with the business or strategic outcome of a technology to ensure immediate relevance for your leadership audience.
- **Visual & Diagrammatic:** Use architecture diagrams and flowcharts to convey complex system designs and AI pipelines efficiently.

## Authority & Integrity
- **High-Authority Sourcing:** Ground all claims in reputable sources such as official documentation, academic papers, and industry-leading reports.
- **Internal Knowledge Base:** Use internal linking to connect related concepts across posts, demonstrating a deep and cohesive expertise.

## Formatting & Structure
- **Skimmable for Executives:** Use descriptive headers, bulleted lists, and "Key Takeaways" to allow busy readers to extract value quickly.
- **Professional Standard:** Maintain high standards of prose and grammar, avoiding overly casual language to preserve the strategic brand.
- **Optimized Meta-Data:** Every post must include a concise description and relevant tags for content organization and discovery.

## Visual Identity
- **Framework-Focused Visuals:** Prioritize diagrams that illustrate strategic frameworks, technical architectures, and AI workflows.
- **Cohesive Branding:** Ensure all visual assets use a consistent style and color palette (aligned with the Cactus "dark" theme) to build a recognizable brand.

## Visual Standards

### Mermaid Diagrams
- **Theme Integration:** Always use the `dark` theme and initialize with the project's primary green accent (`#2bbc8a`).
- **Initialization Snippet:** Use the following initialization block within the diagram definition for consistent styling:
  ```mermaid
  %%{init: {'theme': 'dark', 'themeVariables': { 'edgeLabelBackground': '#121212', 'primaryTextColor': '#fff', 'primaryColor': '#2bbc8a', 'lineColor': '#2bbc8a' }}}%%
  ```
- **Node Styling:** Use `classDef` to define custom styles. Use `#1DE9B6` (or `#2bbc8a`) for positive/neutral actions and `#FF5252` for risks or offensive actions.
- **Layout:** Prefer `graph TD` (Top-Down) for process flows and hierarchies.

### Tables
- **Standard Layout:** Tables should span the full width of the content area.
- **Header Style:** Headers must have a solid background using the primary green accent (`#2bbc8a`) with white bold text.
- **Row Styling:** Use alternating row colors (`#222` and `#1a1a1a`) and hover effects for better readability.

### Captions
- **Placement:** Use the `{{< caption >}}` shortcode immediately before or after a table or complex diagram.
- **Style:** Captions are italicized, muted grey, and feature a 3px solid green (`#2bbc8a`) left border.
- **Content:** Use captions to provide context, title the element (e.g., "**Table 1:**"), or summarize key findings.
