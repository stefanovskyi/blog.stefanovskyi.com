# Oleksandr Stefanovskyi Blog

This is the personal blog of Oleksandr Stefanovskyi, a Strategic Technology Partner. The blog focuses on technology leadership, software engineering, and generative AI topics.

## Project Overview

- **Purpose:** Personal technical blog.
- **Technologies:** 
  - [Hugo](https://gohugo.io/) (Static Site Generator)
  - [Cactus Theme](https://github.com/monkeyWzr/hugo-theme-cactus)
- **Architecture:** Static site generated from Markdown files with TOML front matter.

## Key Directories and Files

- `hugo.toml`: The main configuration file for the site, including site params, menu, and theme settings.
- `content/posts/`: Contains all blog posts as Markdown files.
- `archetypes/`: Templates used when creating new content with `hugo new`.
- `themes/cactus/`: The source code for the Cactus theme.
- `static/`: Static assets such as images and favicons.
- `llms.txt`: A summary of the site's purpose and content guidelines, specifically for AI models.

## Building and Running

### Development
To run the local development server with draft posts enabled:
```bash
hugo server -D
```

### Production Build
To generate the static site in the `public/` directory:
```bash
hugo
```

## Development Conventions

- **Front Matter:** Blog posts use TOML front matter delimited by `+++`.
- **Content Creation:** Use the Hugo CLI to create new posts to ensure proper front matter initialization:
  ```bash
  hugo new posts/my-new-post.md
  ```
- **Styling:** Theme customization is primarily handled through `hugo.toml` parameters. Specific CSS/SCSS overrides would typically go in the `assets/` or `static/` directories depending on the theme's integration.
- **Images:** Post-specific images should be placed in `static/images/` or organized within subdirectories there.

## Content Focus
- Strategic technology planning
- Generative AI in production
- Microservices and system scaling
- Test-driven development (TDD)
- Engineering leadership
