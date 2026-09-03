# Site Structure

This document defines the portfolio sitemap, page types, navigation model, and URL structure before page HTML is created.

## Status
Initial draft. Final project selection and ordering are still to be determined.

## Proposed top-level structure

### Home
Possible sections:
- Introduction / positioning.
- Selected work.
- Short about/background section.
- Footer / contact links.

### Work / case studies
Each major project receives a dedicated case-study page.

Potential projects currently under consideration include:
- AFB / blind and low-vision qualitative coding accessibility work.
- Fiji hospital electronic health record work.
- Beli usability/evaluation work.
- Additional projects to be selected later.

### About
Possible content:
- Background.
- Research/design interests.
- Experience and perspective.
- Resume link.

### Resume
Prefer a downloadable/static PDF rather than requiring a complex embedded viewer.

## URL approach
Prefer directory-style URLs for long-term clarity:

- `/`
- `/about/`
- `/work/afb/`
- `/work/fiji/`
- `/work/beli/`

Exact slugs should be finalized before page creation.

## Navigation
TBD.

Questions to resolve:
- Whether Work needs its own index page.
- Whether About and Resume are separate top-level links.
- Whether individual case studies need local section navigation.
- Mobile navigation behavior.

## Page types
At minimum, plan for:
- Home page.
- Case-study page.
- About page.

Create one canonical case-study implementation before scaling to all projects.

## Case-study page shell
Likely recurring regions:
- Global header.
- Project intro/title.
- Project metadata.
- Main case-study narrative.
- Figures and captions.
- Outcome/reflection.
- Related/next project navigation.
- Global footer.

## HTML timing
Do not create all page HTML during the planning stage. First finalize:
- Top-level sitemap.
- Project list and URL slugs.
- Case-study content hierarchy.
- Core design tokens and layout rules.

Then create the homepage and one reference case-study page before scaling the rest of the site.
