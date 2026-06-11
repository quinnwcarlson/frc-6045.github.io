# FRC 6045 Programming Website

The programming documentation site for **FRC Team 6045 — Sabre Robotics** (Sartell High School), served at [frc-6045.github.io](https://frc-6045.github.io/) via GitHub Pages.

The purpose of this website is to make it easier to find programming-related things that are used or made by FRC 6045 — software setup, how-to guides, auto routines, and documented problems.

## Structure

| File / folder | What it is |
|---|---|
| `index.html` | Homepage — app downloads, guide directory, autos, problems, repos |
| `style.css` | **The one stylesheet for the whole site.** Edit colors/fonts here once and every page updates |
| `howto*.html` | How-to guides |
| `6045autos.html`, `6045*autos.html` | Auto routine documentation by season |
| `documentedproblems.html` | Problems we solved the hard way, written down for next time |
| `templatefornewpages.html` | **Start here to add a new page** — copy it and follow the comments inside |
| `howto*/`, `6045autos/` folders | Screenshots for the matching guide |
| `Sabre_Robotics_Logo.png` | Team logo (transparent background) — used as favicon and nav brand |

## Adding a new page

1. Copy `templatefornewpages.html` and rename it (lowercase, no spaces)
2. Follow the comments inside the file
3. Put screenshots in a new folder named after your page
4. Add a link to your page in the right section of `index.html`
5. Commit and push to `main` — GitHub Pages deploys automatically in ~1 minute

## Design system

- **Colors:** Sabre royal blue `#1A4A91` (sampled from the team logo), logo black `#0E1013`, Driver Station status green/red for callouts. All defined as CSS variables at the top of `style.css`
- **Fonts:** Saira Stencil One (brand/hero — echoes the logo lettering), Saira (headings), IBM Plex Sans (body), IBM Plex Mono (terminal commands)
- **Callouts:** `.callout` (tip), `.callout ok` (success), `.callout warn` (warning/failure)

Maintained by the 6045 programming subteam. Contact: sabrerobotics6045@gmail.com
