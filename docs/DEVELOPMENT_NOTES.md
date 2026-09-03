# Development Notes

Use this file for decisions that are unresolved, implementation discoveries, and temporary notes that should not yet become permanent rules in the other documentation.

## Current decisions
- Deployment target: GitHub Pages.
- Development tooling: Vite is preferred unless later requirements suggest otherwise.
- Initial implementation: plain HTML, CSS, and vanilla JavaScript.
- React is not planned.
- TypeScript is not planned initially.
- Avoid unnecessary dependencies.
- Page HTML will be added after the core structure and design documentation are more stable.

## Workflow
Use ChatGPT primarily for:
- Portfolio strategy.
- Information architecture.
- Content hierarchy and editing.
- Design-system reasoning.
- Accessibility strategy.
- Evaluating implementation screenshots or broader design decisions.

Use Codex/Claude Code primarily for:
- Inspecting the actual repository.
- Creating and editing implementation files.
- Running the development server and builds.
- Debugging HTML/CSS/JavaScript.
- Responsive implementation.
- Repository-wide consistency checks.
- GitHub Pages configuration and deployment debugging.

The repository documentation should act as shared durable context between tools.

## Open questions
- Final portfolio project list and ordering.
- Whether the site needs a dedicated Work index.
- Final navigation structure.
- Final typography and color tokens.
- Layout widths and breakpoint strategy.
- How much local navigation individual research case studies need.
- Whether any interactions justify additional JavaScript or dependencies.
- Final GitHub Pages repository name and therefore Vite `base` configuration.

## Implementation checkpoints
Suggested order:
1. Finalize core documentation.
2. Initialize Git repository and Vite.
3. Implement design tokens and global typography.
4. Implement global page shell/navigation/footer.
5. Build homepage.
6. Build one complete reference case study.
7. Test responsive and accessibility behavior.
8. Scale the established pattern to remaining projects.
9. Run repository-wide QA and cleanup.
10. Configure and validate GitHub Pages deployment.
