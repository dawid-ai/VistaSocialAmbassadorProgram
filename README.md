# Vista Social Ambassador Program — Preview

**Live:** https://dawid-ai.github.io/VistaSocialAmbassadorProgram/

Internal preview repo for the Vista Social Ambassador Program. Three artifacts hosted as static pages via GitHub Pages so the team can review them in a browser before any production deploy.

## What's in here

| Path | What it is |
|---|---|
| `/` (`index.html`) | Landing index linking to all three previews |
| `/pages/ambassador-program-presentation/` | Team-facing scrollable pitch deck — rationale, mechanics, sponsor system, bonus library, launch sequence |
| `/pages/ambassador-program/` | Public landing page where candidates apply — hero, benefit pillars, FAQ, three-step apply flow |
| `/pages/ambassador-lander-template/` | Per-ambassador conversion lander template — `vistasocial.com/a/{slug}` shape, Chris filled in as example |

## Asset structure

The HTML files use relative paths (`../../media/assets/...`, `../chris.jpg`, `bonus/*.png`) that match the original source repo, so:

- `/media/assets/` — Vista Social logos
- `/pages/chris.jpg` — example ambassador photo
- `/pages/{name}/bonus/` — bonus image assets per page

## How GitHub Pages serves it

GitHub Pages is configured to serve from the `main` branch root. URL shape:

- Index: `https://dawid-ai.github.io/VistaSocialAmbassadorProgram/`
- Presentation: `https://dawid-ai.github.io/VistaSocialAmbassadorProgram/pages/ambassador-program-presentation/`
- Public landing: `https://dawid-ai.github.io/VistaSocialAmbassadorProgram/pages/ambassador-program/`
- Lander template: `https://dawid-ai.github.io/VistaSocialAmbassadorProgram/pages/ambassador-lander-template/`

## Updating the preview

1. Edit the HTML in the relevant `pages/` directory
2. Commit + push to `main`
3. GitHub Pages redeploys within ~1 minute

## Source of record

The canonical versions of these files live in the Vista Social KB at `F:\00_PROJECTS\Vista Social\kb\pages\` (private). This repo is a read-only mirror for sharing.
