# 🌐 Web Course — HTML5 & CSS3

This repository contains exercises and small practical examples created while learning front‑end basics using HTML5 and CSS3, from introductory to intermediate/advanced topics.

## 🚀 Overview

The project is a collection of standalone folders. Each folder generally includes an `index.html` demonstrating a specific concept (e.g., links, tables, forms, CSS selectors, floats, units, etc.). Files are intended to be opened directly in a browser; there is no build step or backend.

## 🧰 Stack Detection

- Language: HTML5 and CSS3
- JavaScript: minimal/static (only where demonstrations require it)
- Frameworks/Libraries: none detected
- Package manager: none detected (no `package.json`, `composer.json`, or similar)
- Entry points: multiple `index.html` files across module directories (open directly in a browser)

## 📂 Project Structure

The repository is organized by course modules. Examples include:

- `MODULO 2 - HTML5 & CSS3, Introducao/`
  - Foundations and basic structure (`001`, `002`, ...)
  - Practical exercises and first website (`014`, `016`)
  - CSS selectors and button styling (`020`, `030`)
  - Semantic elements with floats (`033`)
  - CSS units (`034`)
  - Final module exercise (`037~040`)

- `MODULO 3 - HTML5 INTERMEDIÁRIO & AVANÇADO/`
  - Hyperlinks: common patterns, targets, downloads, bookmarks, email/phone links
  - Tables: intro, CSS styling, `caption`, `colspan`, `rowspan`, and exercises
  - General tips: comments, entities, symbols
  - Forms: intro, GET/POST, input attributes and types (color, checkbox, radio, range, hidden), and basic security notes
  - Example paths:
    - `MODULO 3 - HTML5 INTERMEDIÁRIO & AVANÇADO/04. FORMULÁRIOS/075. FIELDSET & LEGEND/index.html`
    - `MODULO 3 - HTML5 INTERMEDIÁRIO & AVANÇADO/04. FORMULÁRIOS/076. INPUT RESET E BUTTON/index.html`
    - `MODULO 3 - HTML5 INTERMEDIÁRIO & AVANÇADO/04. FORMULÁRIOS/078. PATHS RELATIVAS E ABSOLUTAS/exemplo_1/index.html`
    - `MODULO 3 - HTML5 INTERMEDIÁRIO & AVANÇADO/04. FORMULÁRIOS/078. PATHS RELATIVAS E ABSOLUTAS/exemplo_2/index.html`

Each lesson folder typically contains an `index.html` and may include supporting assets under `assets/` (e.g., `css/`, `js/`, `images/`).

## ⚙️ Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- Optional: a code editor (e.g., PhpStorm, VS Code) if you’d like to explore/edit the source

## ▶️ Quick Start

No build tools or servers are required — this is a static project.

```bash
git clone https://github.com/fernandes-kaue/cursoDeWeb.git
cd cursoDeWeb
# pick any lesson directory and open index.html in your browser
```

Alternatively, serve a folder locally (avoids some `file://` restrictions and enables relative path testing):

- Using Python 3 (no install needed on most systems):
  ```bash
  # from the lesson folder you want to serve
  python3 -m http.server 8000
  # then visit http://localhost:8000 in your browser
  ```
- TODO: If a package manager is adopted later, consider adding a convenience dev server script (e.g., `live-server`, `browser-sync`).

## 📜 Scripts

No automation scripts are configured in this repository.

- TODO: If tooling is introduced later, document commands here (e.g., start, build, format, lint).

## 🔐 Environment Variables

None. This is a static collection of examples and does not rely on environment variables.

## 🧪 Tests

There are no automated tests configured. Verification is performed manually by opening pages in the browser.

- TODO: Consider adding simple checks (e.g., HTML validation, link checks) if needed.

## ℹ️ Notes

- Some form examples post to an external demo endpoint (`https://sys4soft.com/udemy/forms/index.php`) purely for demonstration. No local server is required.

## 📄 License

Educational use only at the moment.

- TODO: Choose and add an explicit open‑source license (e.g., MIT) or clarify usage restrictions.
