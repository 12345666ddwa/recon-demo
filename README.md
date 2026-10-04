# RECon · App Demo (storyboard replica + interactive layer)

Screens are the team's own Canva storyboard pages, captured at 2x resolution (2560 px wide)
and assembled into a clickable app demo. No redrawn visuals: what you see is the actual design.

## Run it

- Open `index.html` in Chrome / Edge (keep the `assets/` folder next to it)
- Press F11 for fullscreen during the pitch
- Keep it offline-safe: no internet needed

## Interactions

| Element | Action |
|---|---|
| Nav: Home / About / Feasibility / My Constructions | switches to the matching screen |
| Nav: Tools | opens the 4-item tools dropdown |
| Home: "View feasibility" | opens the feasibility screen |
| Feasibility: "Analyse my building" | plays the scan animation overlay |
| Left / right screen edges | prev / next screen (arrow appears on hover) |
| Keys 1-9, 0 | jump to screen 1-10 |
| Esc | close overlays |

## Screens (1-10)

1-3 Home variants, 4 What's around, 5 Preventing collapse, 6 Data sources, 7 Phone QR,
8 About us, 9 Build smarter (feasibility), 10 Monitoring & Reporting & Verification.

## Notes

- Concept demo for the Climate Hack-tion 2026 pitch. Illustrative content.
- Captured from the team's Canva presentation via the browser debugging protocol
  (pipeline scripts in `reference/` in the workspace copy). If the design changes,
  the screens can be re-captured and dropped into `assets/pages/` (same filenames).
