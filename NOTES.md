# Furnace of Prayer Ministry — build notes

- **Type:** Lovable rebuild (CLAUDE.md §0 case B). Old site: lovable.app.
- **Palette:** `fire` — matches the church's existing warm fire palette (orange/red on dark ground) from
  their old site, per operator instruction. Do not swap to a cooler palette in refine.
- **Theme/imagery:** altar fire, burning coals, night prayer, flame.
- **Hero:** "Igniting revival" / "through prayer." — Leviticus 6:13 ("The fire on the altar must never go out.")
- **Moments heading:** "Five flames, one fire"

## Real details used (from WDF onboarding, NOT placeholders)

These came from the church's app onboarding and **override** whatever the old Lovable site shows:

- Service times: Sundays 10:00 · Wednesdays 17:00 · Fridays 17:00
- Address: FL 10 Itlameng Street, Kagung, Kuruman
- Pastor's cell: 060 459 3822 (wired as `tel:+27604593822` on the "Call the church" CTA)

Applied by hand-editing `index.html` after the v1 generator run, since `generate.py` has no flags for
these fields. **If Phase 2 screenshots of the old site show different times/address, trust the onboarding
data above, not the screenshots** — the operator flagged that the two sources disagree.

## Still open for Phase 2 (when old-site screenshots arrive)

- Vision/about copy, ministries detail, any other real wording from the old Lovable site.
- Logo (if the church has one from onboarding) — not yet applied.
