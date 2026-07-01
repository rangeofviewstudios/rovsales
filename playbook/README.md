# ROV Sales Playbook

The hub. Organized by **who we're selling**, not by artifact type. When you sit down to
attack a vertical, you open one file and everything is there: offer, channels, angles,
scripts, objections.

## How it's built

- **`00-SPINE.md`** — the engine every vertical inherits: the four offers + package,
  the A/B/C angle system, the voice/copywriting rules, objections, tracking. Read it once.
- **`verticals/`** — one self-contained sheet per target. Same 7-section skeleton every
  time, so you always know where to look. This is what you act on.
- **`_TEMPLATE.md`** — copy this to start a new vertical. Fill the brackets, that's it.

## Verticals

| Sheet | Status | Lead wedge |
|---|---|---|
| [restaurants](verticals/restaurants.md) | live | website + own-your-customers (vs DoorDash's 30%) |
| [real-estate](verticals/real-estate.md) | live | personal brand + referral database (vs renting Zillow leads) |
| _hvac_ | todo | missed-call leak |
| _roofing_ | todo | missed-call leak |

## To add a vertical

1. Run `industry-research` on it if there's no fresh brief (< 6 months) in `RESEARCH/`.
2. `cp _TEMPLATE.md verticals/{name}.md`, fill every bracket from the brief.
3. Name the three money leaks in *their* words. That's the whole sheet.
4. Add a row to the table above.

## Related, not duplicated

- **`../../mark-outreach-playbook.md`** — the rep-facing view. Just scripts + tracking,
  no strategy. It pulls from these sheets; don't maintain scripts in two places.
- **`../../07_tools/playbooks.md`** — the *build* flows (design/dev/mock). Different job:
  this hub sells, that one builds.
