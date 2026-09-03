# Design System

This document translates the portfolio style guide into implementation rules. It should be updated as visual decisions become stable.

## Status
In progress. Do not treat unspecified values as finalized.

## Principles
- Support fast scanning without reducing research projects to surface-level visuals.
- Prioritize readable long-form case studies.
- Keep research evidence, findings, and design implications visually connected.
- Use a restrained system with consistent tokens rather than page-specific styling.
- Accessibility requirements are part of the design system, not a final QA pass.

## Color
TBD from the style guide.

Document:
- Background colors.
- Primary and secondary text colors.
- Accent colors.
- Border/divider colors.
- Interactive states.
- Focus indicator colors.
- Required contrast relationships.

## Typography
TBD from the style guide.

Document:
- Font families and fallbacks.
- Heading scale.
- Body sizes.
- Line heights.
- Weights.
- Letter spacing where applicable.
- Caption and metadata styles.
- Long-form reading width.

## Spacing
TBD.

Prefer a small reusable spacing scale rather than arbitrary values.

## Layout
TBD.

Decisions to define:
- Maximum site/container width.
- Long-form reading-column width.
- Grid behavior.
- Figure widths.
- Full-bleed or breakout media rules.
- Section spacing.

## Breakpoints and responsive behavior
TBD.

Breakpoints should be chosen because the layout needs to change, not because of specific device names.

## Components
Define visual and interaction rules as components become necessary.

Likely components:
- Global navigation.
- Footer.
- Project cards.
- Case-study metadata.
- Buttons and text links.
- Figures and captions.
- Callouts or key findings.
- Method summaries.
- Next-project navigation.

## Images and figures
- Figures should support the research narrative rather than function as decoration.
- Preserve readable diagrams on smaller screens.
- Provide explicit width and height where practical to reduce layout shift.
- Use meaningful alternative text when the image conveys information.
- Use empty alt text for decorative imagery.
- Captions should explain relevance when the visual alone is insufficient.

## Interaction
- Prefer native browser interaction patterns.
- Avoid interactions that are available only on hover.
- Ensure focus and hover states are visually distinct.
- Motion should be purposeful and nonessential.

## Accessibility
- Maintain visible keyboard focus.
- Preserve logical source order across responsive layouts.
- Do not rely on color alone to communicate state.
- Interactive targets should be comfortably usable at touch sizes.
- Respect reduced-motion preferences.
- Screen-reader complexity should not be increased merely to reproduce a visual pattern.
