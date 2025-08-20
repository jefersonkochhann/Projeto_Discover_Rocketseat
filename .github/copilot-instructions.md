# Copilot Instructions for AI Coding Agents

## Project Overview
This is a static web project consisting of an `index.html` file, a `style.css` stylesheet, and an `assets/` directory containing images and SVGs. The project does not use a build system, frameworks, or external dependencies. All logic and styling are handled directly in HTML and CSS files.

## Key Files & Structure
- `index.html`: Main HTML file. All markup is here. Look for semantic structure and image references.
- `style.css`: Contains all styling rules. Customizes layout, colors, and responsive design.
- `assets/`: Stores images and SVGs. Subfolder `Mobile/` contains mobile-specific assets.

## Patterns & Conventions
- **Image Usage**: Images are referenced with relative paths (e.g., `assets/avatar.png`). Mobile assets are in `assets/Mobile/`.
- **Responsive Design**: The project uses separate images for desktop and mobile backgrounds. Check CSS for media queries and HTML for conditional image usage.
- **No JavaScript**: There is no JavaScript in the project. All interactivity is handled via CSS (e.g., hover effects, transitions).
- **No Build Step**: Changes to HTML/CSS are reflected immediately. No compilation or bundling required.
- **No Tests**: There are no automated tests or test files.

## Developer Workflow
- **Edit HTML/CSS**: Directly modify `index.html` and `style.css`.
- **Preview**: Open `index.html` in a browser to view changes. No local server required.
- **Add Assets**: Place new images/SVGs in `assets/` or its subfolders. Reference them in HTML/CSS using relative paths.

## Examples
- To change the avatar image, update the `src` attribute in `index.html` to point to a different file in `assets/`.
- To adjust mobile backgrounds, edit the relevant CSS media queries and reference images in `assets/bg-mobile.jpg` or `assets/bg-mobile-light.jpg`.

## Recommendations for AI Agents
- Focus on semantic HTML and clean, maintainable CSS.
- When adding new assets, follow the existing directory structure and naming conventions.
- Ensure all image paths are correct and relative to the project root.
- Document any new patterns or conventions in this file for future agents.

---
_Last updated: 10 de agosto de 2025_
