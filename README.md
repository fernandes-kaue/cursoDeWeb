# 🌐 Web Course — HTML5 & CSS3

This repository contains exercises and small practical examples created while learning front‑end basics using HTML5 and CSS3, from introductory to intermediate/advanced topics.

## 🚀 Overview

The project is a collection of standalone folders. Each folder generally includes an `index.html` demonstrating a specific concept (e.g., links, tables, forms, CSS selectors, floats, units, etc.). Files are intended to be opened directly in a browser; there is no build step.

## 🧰 Stack Detection

- Language: HTML5 and CSS3
- JavaScript: minimal/inline (only where demonstrations require it)
- Frameworks/Libraries: none detected
- Package manager: none detected (`package.json` and `composer.json` not present)
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

Note: Each lesson folder typically contains an `index.html` (and sometimes additional `.html` files) that illustrate the topic.

## ⚙️ Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- Optional: a code editor (e.g., PhpStorm, VS Code) if you’d like to explore/edit the source

## ▶️ Setup & Run

No build tools or servers are required — this is a static project:

1. Clone the repo:
   ```bash
   git clone https://github.com/fernandes-kaue/cursoDeWeb.git
   cd cursoDeWeb
   ```
2. Navigate to any lesson folder of interest.
3. Open `index.html` directly in your browser (double‑click or use your editor’s “Open in Browser”).

Optional (serve locally for better navigation or to avoid file:// URL restrictions):

- Use a simple static server, for example with Python:
  ```bash
  # from the lesson folder you want to serve
  python3 -m http.server 8000
  # then visit http://localhost:8000 in your browser
  ```
- TODO: Add a dev convenience script (e.g., `live-server` or `browser-sync`) if a package manager is adopted later.

## 📜 Scripts

No automation scripts are configured in this repository.

- TODO: If tooling is introduced later, document commands here (e.g., start, build, format, lint).

## 🔐 Environment Variables

None. This is a static collection of examples and does not rely on environment variables.

## 🧪 Tests

There are no automated tests configured. Verification is performed manually by opening pages in the browser.

- TODO: Consider adding simple checks (e.g., HTML validation, link checks) if needed.

## 📄 License

Educational use only at the moment.

- TODO: Choose and add an explicit open‑source license (e.g., MIT) or clarify usage restrictions.
