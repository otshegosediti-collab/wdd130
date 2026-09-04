# AGENTS

## Purpose
This repository is a static HTML/CSS learning workspace for BYU Pathway Worldwide WDD 130.
AI coding agents should treat it as a beginner-oriented student exercise collection, not a production app.

## Key guidance
- The workspace contains only static HTML, CSS, images, and simple page layouts.
- Do not write or edit complete student assignment files as a solution.
- Prefer explanations, concepts, and partial examples that help the student think through the fix.
- Use the project structure to understand scope:
  - `week01/` through `week05/` contain exercise files.
  - `wwr/` contains a sample site.
- There is no build system or backend; use plain HTML/CSS conventions.
- Google-specific code is exercise-local: `week04/header-layout.html` demonstrates Google Fonts and `week04/styles/layout.css` keeps a fallback font stack.
- Preserve `preconnect`/font links and fallback fonts when working on that exercise; do not turn the example into a site-wide Google dependency.
- Any new remote Google asset requires network access and should keep a local or system fallback when practical. Keep asset paths relative to the HTML file's folder.
- For Google-hosted images or other external media, preserve or add clear licensing/attribution documentation; see `week01/images/image-license.md`.

## Notes for agents
- Respect the existing tutor role in `.github/copilot-instructions.md` and `CLAUDE.md`.
- If asked to help, explain semantic HTML, CSS selectors, box model, layout, or responsive design clearly.
- Avoid generating full pages or full CSS files; guidance should be incremental and educational.
