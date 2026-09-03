# Portfolio Agent Instructions

## Project purpose
This repository is a personal UX/HCI research portfolio. The site should foreground research reasoning, evidence, design decisions, and outcomes while remaining easy to maintain and deploy.

## Intended stack
- Vite for local development and production builds.
- Plain HTML5.
- CSS.
- Vanilla JavaScript.
- No React unless explicitly approved.
- No TypeScript unless explicitly approved.
- GitHub Pages as the deployment target.

## General development rules
- Prefer the simplest implementation that satisfies the requirement.
- Prefer native HTML and CSS behavior before adding JavaScript.
- Do not install new npm packages without explicit approval.
- Do not introduce frameworks, component libraries, or build plugins without explicit approval.
- Reuse existing styles and patterns before creating new ones.
- Do not make unrequested changes outside the files or feature being worked on.
- Do not rewrite portfolio content unless explicitly asked.
- Never invent research findings, metrics, participant details, methods, outcomes, or project claims.
- When a requirement is underspecified, report the assumption rather than silently making a major design decision.

## GitHub Pages constraints
- The production build must remain deployable as a static site on GitHub Pages.
- Avoid server-only functionality.
- Use paths that work when the site is hosted under a repository subpath.
- Keep Vite base-path configuration compatible with the eventual GitHub Pages URL.

## Accessibility
- Use semantic HTML first.
- Maintain a logical heading hierarchy.
- All interactive functionality must be keyboard accessible.
- Provide clearly visible focus states.
- Do not use positive `tabindex` values.
- Do not use `role="application"` on the application shell, reading content, or case-study regions.
- Use ARIA only when native HTML cannot provide the needed semantics.
- Preserve sensible DOM/read order across breakpoints.
- Do not hide meaningful content from assistive technologies.
- Decorative images should use empty alt text.
- Respect `prefers-reduced-motion` for nonessential motion.

## Code quality and validation
Before finishing an implementation task when applicable:
- Run the production build.
- Check for console errors.
- Check for broken internal links and asset paths.
- Test the relevant responsive states.
- Check keyboard interaction for changed interactive components.
- Summarize what changed and any assumptions or unresolved issues.

## Source-of-truth documents
Read these before making broad structural or visual changes:
- `docs/DESIGN_SYSTEM.md`
- `docs/CONTENT_GUIDE.md`
- `docs/SITE_STRUCTURE.md`
- `docs/DEVELOPMENT_NOTES.md`
