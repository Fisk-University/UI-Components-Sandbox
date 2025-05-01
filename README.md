# 🎨 UI Components Sandbox

This repository is a development sandbox for building and organizing the static UI components used in the [Rosenwald Project](https://github.com/Fisk-University). These components are derived from the official Figma design system created for the digital collection website at Fisk University.

> **Figma Link:** [Rosenwald Project Design File](https://www.figma.com/design/Qy3lGxQZLrAd4cOQ8IECBe/Fisk?node-id=858-653&t=qAtodchDZWe7qUgN-0)

## 📌 Purpose

This sandbox exists to:
- Help junior developers practice turning Figma designs into clean, semantic HTML/CSS/JS
- Isolate and test each component in a simple environment with no framework dependencies
- Create a living library of frontend UI elements for reuse in Omeka S themes or other environments

---

## 🗂 Folder Structure

Each component from the Figma file should be placed in its own folder under `/components`, like this:

```
/components
  /Header
    index.html
    styles.css
    script.js
  /Dropdown
    index.html
    styles.css
    script.js
  /Button
    ...
```

Each folder represents one self-contained component. You may optionally add an `assets/` subfolder if a component includes images or fonts.

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Fisk-University/UI-Components-Sandbox.git
   cd UI-Components-Sandbox
   ```

2. **Open a component folder**
   Open any `index.html` file inside a component folder directly in your browser to view it.

3. **Edit or Add Components**
   - Follow the structure above when adding new components.
   - Use semantic HTML5.
   - Use plain CSS and JavaScript (no frameworks or build tools).
   - Keep your code clean, accessible, and well-commented.

---

## 📀 Development Guidelines

- Match the Figma layout, spacing, and colors as closely as possible.
- Prioritize accessibility (`aria-label`, tab order, contrast, etc.).
- Use class names that are clear and reusable (e.g., `btn-primary`, `dropdown-list`).
- All styles should be written in `styles.css` unless inline styles are unavoidable.
- Scripts should only include behavior specific to the component (e.g., toggle dropdown).

---

## 🧪 Testing Your Component

Each `index.html` file should:
- Be viewable without a web server (openable by double-click)
- Contain a `<div class="preview">` section where the component is rendered
- Optionally include example usage or notes for others who use the component

---

## ✨ Future Integration

Once stable, these components may be ported into:
- A unified Omeka S theme
- A CMS component library
- An internal style guide for the Fisk University digital archive initiative

---

## 👩🏽‍💻 Contributors

This repo is maintained by the Rosenwald Project development team. Junior developers and volunteers are encouraged to contribute as part of their frontend learning experience.

---

## 📄 License

This repository is purely maintained for internal use.
