# Diversitätssensibler Umgang mit Künstlicher Intelligenz - Project Context

## Project Overview
This project contains the "Diversitätssensibler Umgang mit Künstlicher Intelligenz" guide (formerly SocialAI), a single-page web document designed to guide social workers in the ethical and professional use of Artificial Intelligence, focusing on AI Literacies and feminist prompting.

The guide focuses on:
*   **Human-in-the-Loop:** Emphasizing professional judgment over AI output.
*   **EPIC Model:** A framework for ethical AI usage (Ethics, Policy, Intersectoral, Community).
*   **Prompt Engineering:** A 5-step formula for creating safe and effective prompts (Role, Context, Task, Format, Constraints).
*   **Risk Awareness:** Addressing hallucinations, bias, and data privacy.

## Directory Overview
This directory serves as the repository for the standalone web page. It is a "Non-Code" project in the sense that it doesn't require compilation or a complex build chain, but it does contain front-end code (HTML/CSS/JS).

## Key Files

### `index.html`
The core file of the project. It is a self-contained HTML document that includes:
*   **Structure:** Semantic HTML5 markup for the guide's content sections (Purpose, EPIC Model, Risks, Prompting, etc.).
*   **Styling:** Embedded CSS (in the `<head>`) defining the design system, including variables for colors (e.g., `--col-primary`, `--col-accent`), typography ('Inter', 'Merriweather'), and responsive layout (CSS Grid/Flexbox).
*   **Functionality:** Embedded JavaScript (at the bottom) providing a client-side full-text search feature (`filterContent` function).

### `GEMINI.md`
This file. It serves as the context and documentation for AI agents interacting with this directory.

## License
This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

## Usage & Development

*   **Viewing:** The `index.html` file can be opened directly in any modern web browser. No server is strictly required for local viewing.
*   **Editing:** All content, styles, and logic are located within `index.html`. Changes should be made directly to this file.
*   **Design System:** The project uses a specific color palette and typography defined in the `:root` CSS variables. Adhere to these conventions when making UI updates.
    *   Primary Color: Deep Petrol (`#1E3A4C`)
    *   Accent Color: Terracotta (`#D97757`)
    *   Success Color: Muted Teal (`#2A9D8F`)
*   **No Build Step:** There are no build scripts (npm, make, etc.). The file is ready to use as-is.
