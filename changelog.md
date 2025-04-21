# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2025-04-21

### Fixed

- Markdown format in `changelog.md`;
- Reference to [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) website;
- ul lists in order to proper render the ol

### Changed

- main.css, index.html, testing.html: Sections used in comments with the "Section >" and "< Section" elements -> "#region Section", "#endsection"
- index.html: centered the header;
- typography designs;
- directory hierarchy;

### Added

- ordered lists;
- typography elements;
- Source Code Pro and Source Sans fonts;
- Github social banner;

## [0.1.0] - 2025-04-06

### Added

- Initial project structure setup after `git init`;
- `.gitignore`: Basic file to ignore workstation artifacts (`.directory`);
- `index.html`: Main personal landing page including:
  - Basic HTML5 structure;
  - SVG logo embedded with hover effects;
  - Header section with name and brief description;
  - Content sections for Hobbies and Socials (placeholder);
  - Links to `reset.css`, `main.css`, and `simple-flag.svg` favicon;
  - Basic footer;
- `main.css`: Custom stylesheet containing:
  - `@font-face` import for `AndadaPro`;
  - CSS variables for theming (light/dark mode via `prefers-color-scheme`);
  - Basic responsive design using media queries;
  - Styling for typography (`h1`, `h2`, `h3`);
  - SVG logo styling (`.logo`, `.rear-flag`, `.front-flag`, hover effects);
  - `.divider` style;
  - `section` styling with hover effects;
  - Nested list styling (`ul`, `li`, `.arrow-list`);
  - Basic footer styling;
- `reset.css`: Included Meyer's CSS Reset (v2.0) for browser style normalization;
- `simple-flag.svg`: SVG file used for the embedded logo and as the site favicon;
- `testing.htm`: HTML page designed for testing CSS styles across a wide range of standard HTML elements, including:
  - Text elements (headings, paragraphs, inline formatting, blockquote, pre, code);
  - List elements (ordered, unordered, definition);
  - Link elements;
  - Media elements (img, figure);
  - Table elements;
  - Form elements (fieldset, legend, input types, textarea, select, button);
  - Interactive elements (details/summary);
