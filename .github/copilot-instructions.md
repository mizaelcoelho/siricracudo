# Copilot Instructions for AI Agents

## Project Overview
This is a static website project structured for a simple user flow: login, signup, and home. The main entry point (`index.html`) immediately redirects users to `pages/home.html`. All UI logic is handled via HTML and CSS; there is no JavaScript or backend integration present.

## Directory Structure
- `index.html`: Redirects to the main home page.
- `pages/`: Contains individual HTML files for `home`, `login`, and `signup`.
- `css/`: Contains CSS files for each page, named to match their corresponding HTML files.
- `img/`: Stores static image assets.

## Key Patterns & Conventions
- **Page Routing**: All navigation is handled by direct links or meta refresh redirects. No SPA or client-side routing.
- **Styling**: Each page has a dedicated CSS file. Example: `home.html` uses `home.css`.
- **No Build Step**: The project is pure HTML/CSS. No build tools, package managers, or test frameworks are present or required.
- **No External Dependencies**: All resources are local; there are no CDN or third-party libraries.

## Developer Workflow
- **Previewing**: Open any HTML file directly in a browser. The default entry is `index.html`, which redirects to `pages/home.html`.
- **Editing**: Update HTML in `pages/` and corresponding CSS in `css/`. Add images to `img/` as needed.
- **Adding Pages**: To add a new page, create an HTML file in `pages/` and a matching CSS file in `css/`.

## Examples
- To change the home page style, edit `css/home.css`.
- To update the login form, edit `pages/login.html` and `css/login.css`.

## Special Notes
- There is no JavaScript, backend, or dynamic content. All logic is static and declarative.
- If adding new features, follow the pattern of pairing each HTML page with a CSS file.

---
For questions about project structure or conventions, review this file or the directory layout. If unclear, ask for clarification before making major changes.
