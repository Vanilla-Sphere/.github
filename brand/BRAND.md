# Vanilla Sphere · brand one-pager

**Explore the sky. Connect the observations. Discover what moves.**

An independent student astronomy team participating in NASA Space Apps Challenge 2026, exploring Planet X and SPHEREx. **Vanilla Sphere is independent and is not affiliated with or endorsed by NASA.**

## Palette

| Color | Hex | Usage |
| --- | --- | --- |
| Observation navy | `#15345A` | Primary headings, wordmark, GitHub badge background; existing README color |
| SPHEREx teal | `#147D87` | Links, selected states, secondary badges; existing README color |
| Vanilla | `#F7F4EB` | Main page and slide background; warm, quiet contrast |
| Deep sky | `#07173F` | Dark slides, social backgrounds; Space Apps Deep Blue |
| White | `#FFFFFF` | Text on navy, teal and Deep Sky; clean panels |
| Blue Yonder | `#2E96F5` | Plot highlights, focus accents and data points; Space Apps palette |
| NASA lettering red | `#DB240B` | Reserved for supplied Space Apps logo colorways; not a team identity color |

Use navy or teal text on Vanilla/white; white text on navy, teal or Deep Sky. Blue Yonder is an accent, not small text on Vanilla/white. Label plot series and use shape or line style as well as color. Badge hex values omit `#`: `15345a`, `147d87`; use white label text. Reusable CSS tokens: `assets/vanilla-sphere/palette.css`.

The guide's **Rocket Red is `#E43700`**; the supplied Wikimedia Motif uses **`#DB240B`**. This package consistently uses the latter for NASA lettering. Team colors do not authorize recoloring the Space Apps mark.

## Type, voice and visual tone

**Fira Sans Medium/Semibold** for titles; **Overpass Regular** for body, captions and UI. Both are libre (SIL Open Font License) and follow the supplied Space Apps guide. Use a system sans-serif fallback. The team SVG contains Fira Sans Medium outlines, so it needs no font installation. Use live text for the tagline and page content.

Be calm, precise and evidence-first. Distinguish observations, hypotheses and uncertainty. Prefer “candidate moving source” to “Planet X discovered.” Use restrained star maps, coordinate grids, spectra and labeled plots. Leave room for captions, units and sources. Avoid agency seals, mission patches and dramatic discovery claims.

## Logo use · do / don't

- **Do** use the horizontal Space Apps Default as the primary event mark. Unsuffixed filenames and `-full` are identical, with INTERNATIONAL and the original registration symbol. Use `-compact` for the supplied contemporary NASA / SPACE APPS / CHALLENGE arrangement. Motif is for self-contained applications such as stickers. Orbit-only is for very small placements.
- **Do** use black + red on light backgrounds and white + red on dark backgrounds. Keep the aspect ratio. All SVGs have transparent backgrounds; dark backgrounds belong to the surrounding layout.
- **Do** leave clear space outside the SVG bounds. A conservative team layout rule is **at least one-third of the mark's overall height on every side**. Keep Vanilla Sphere in a separate text block beyond that space. Consult the supplied guide's Default, Motif and Small diagrams (printed pages 3–5) for their construction grids; this team rule is additional layout guidance.
- **Do** use the navy Vanilla Sphere wordmark on light backgrounds. Keep it visually separate from the event mark and pair it with the independent-team disclaimer. Set the tagline as readable body text beneath the team name.
- **Don't** stretch, rotate, rearrange, crop, add outlines, recolor, or merge the Space Apps logo with the team name. Don't use it over busy imagery or shrink lettering until it becomes illegible; switch to Orbit instead.
- **Don't** add the NASA insignia or worm, use “official NASA team,” or imply agency affiliation, sponsorship or endorsement. Orbit-only identifies Space Apps, not Vanilla Sphere; prefer the team wordmark as the repository identity.

## Sources and delivery

Space Apps Brand Guide, updated May 23, 2025, and supplied Wikimedia SVGs in `refs/`. Full Default and Motif preserve their vector paths. Compact is a local closed-path trace of `Space_Apps_Logo_Color_hi.png`, visually checked against the supplied compact references; it is a reconstruction, not a newly issued official master. Source assets remain untouched. Event marks retain their owners' rights; this package grants no NASA endorsement or trademark license.

See `HANDOFF.md` for exact filenames, checks, source limitations and `.github` integration notes.
