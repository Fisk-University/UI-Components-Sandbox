# UI-Components-Sandbox

## Project Overview

This repository is part of the **Rosenwald Digital Archive**, a Mellon-funded digital humanities initiative at Fisk University. The main project documents the impact of Julius Rosenwald, a philanthropist who funded thousands of schools for African-American children in the segregated South.

This repository contains static, front-end components built for the initiative. The primary website is being built using **Omeka S**, a content management system tailored for digital archives. To support scalable development, this **UI Components Sandbox** was created to help developers — especially junior devs — turn Figma mockups into modular, reusable front-end components.

These components will later be integrated into the live Omeka S theme. The sandbox allows for focused, independent development and review of each element, making it easier to maintain design consistency, test responsiveness, and build accessibly.

## Folder Structure

Each UI component should live in its own folder inside the root of the project. For example:
`Dropdown/`, `Header/`, `Footer/`, `Card/`

Each component folder must include:
- `index.html` — Static markup
- `style.css` — Component-specific styles
- `script.js` — Optional JS interactivity (vanilla only)

## How to Use the Repository

1. **Clone the repo**:
   ```bash
   git clone https://github.com/YOUR-ORG-NAME/ui-components-sandbox.git
2. Navigate to a component folder and open `index.html` in your browser to preview.

3. To contribute a new component:
- Create a new folder named after your component (e.g., /search-bar/)
- Add the required files: index.html, style.css, and optionally script.js
- Test your component in the browser
- Submit a pull request with a clear title and description

## Style Guidelines

- Use only vanilla HTML, CSS, and JavaScript.  
  Do not use frameworks (e.g., React, Vue) or preprocessors like SCSS.
- Follow consistent naming conventions.  
  Use lowercase and dashes for all folders and files (`search-bar`, not `SearchBar`).
- Keep each component self-contained.  
  Avoid global styles or scripts. Each component should be modular and scoped to its folder.
- Prioritize accessibility.  
  Use semantic HTML elements, keyboard-navigable structures, and appropriate ARIA attributes to ensure your component is usable by all.
  
## Frontend UI design- [Figma Link](https://www.figma.com/design/Qy3lGxQZLrAd4cOQ8IECBe/Fisk)
