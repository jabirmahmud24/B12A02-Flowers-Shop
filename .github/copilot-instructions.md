# Copilot Instructions for B12A02-Responsive-Flowers

## Project Overview
This is a responsive flower shop web assignment built with HTML and CSS. Tailwind CSS utility classes are used directly in HTML, but there is no build step or Tailwind config file. All assets are local, and no external UI libraries (like DaisyUI or Flowbite) are allowed.

## Key Files & Structure
- `index.html`: Main page, contains all sections (navbar, banner, plants, plant lover, join, footer).
- `style.css`: Custom styles for branding and layout tweaks. Tailwind is used via CDN in HTML, not via PostCSS.
- `assets/`: All images and icons used in the site.
- No JavaScript build system or framework is present.

## Developer Workflow
- Edit HTML and CSS files directly. No build or test commands are required.
- Use Tailwind utility classes in HTML. Custom classes (e.g., `.holud`, `.btn`) are defined in `style.css`.
- For responsiveness, use Tailwind's responsive classes (e.g., `sm:`, `md:`, `lg:`) in HTML.
- For custom fonts, use Google Fonts links in the HTML `<head>`.
- To preview, open `index.html` in a browser. No local server is required.

## Patterns & Conventions
- All layout and styling is done via Tailwind classes and a few custom CSS classes.
- Section structure follows the assignment requirements (see `README.md`).
- No JavaScript except for optional alert on "Add to Cart" (if implemented).
- No external CSS frameworks or libraries.
- Images are referenced with relative paths from the `assets/` folder.

## Integration Points
- Tailwind CSS is loaded via CDN in the HTML `<head>`. No config file is present.
- Font Awesome is loaded via CDN for icons.
- Google Fonts are loaded via CDN for typography.

## Examples
- Responsive grid: `<div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4">`
- Custom color: `<span class="holud">` uses `.holud` in `style.css`.
- Button: `<button class="btn">ADD TO CART</button>` uses `.btn` in `style.css`.

## Special Notes
- Do not add build tools, package.json, or Tailwind config files.
- Do not use placeholder text; use relevant content as per assignment.
- Follow the section order and structure described in `README.md`.
- For mobile, use Tailwind's responsive classes and hide/show elements as needed.

---
For questions or unclear conventions, review `README.md` for assignment requirements and refer to existing HTML/CSS for examples.
