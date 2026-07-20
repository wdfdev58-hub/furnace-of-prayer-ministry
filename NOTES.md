# Furnace of Prayer Ministry — build notes

- **Type:** Lovable rebuild (CLAUDE.md §0 case B). Old site: furnaceofprayerministry.lovable.app.
- **Palette:** `fire` — kept as-is from v1 (Katlego's template). It already matches the church's own warm
  fire palette (orange/red/gold on a near-black ground) closely; no palette changes made in the refine pass.
- **Phase 2 refine done:** 2026-07-20, from operator-supplied screenshots of the old Lovable site (6 images,
  `/home/wdf-websites/screenshot/`).

## Real content carried across from the old site

- Hero tagline "Igniting revival / through prayer." (kept from v1, matches their real tagline).
- Hero sub-line: James 5:16 ("The effectual fervent prayer of a righteous man availeth much.") — now the
  actual hero quote, replacing the v1 generic paragraph.
- Full vision paragraph (Leviticus 6:13 framing) — now the `#vision` section, verbatim from the brief.
- "Five Flames, One Fire" mission section — all 5 pillars (Gather/Equip/Intercede/Release/Serve) with their
  real descriptions and scripture refs (Acts 1:14, Luke 11:1, Ezekiel 22:30, Isaiah 6:8, James 2:17),
  transcribed from screenshot 3. Replaced the v1 generic "Ministries" grid and "What to expect" cards —
  those were invented filler; the real Five Flames content covers the same ground authentically.
- Closing verse band: Mark 11:17 ("My house shall be called a house of prayer for all nations"), transcribed
  from screenshot 4, added as a modest quote section before the Visit CTA.
- Service names kept from the old site ("Early Morning Altar", "Midweek Intercession", "Night of Fire") —
  **times corrected** to WDF's onboarding data (see below); the operator confirmed the old site's times were
  wrong even though the names should stay.

## Real details used (from WDF onboarding, override the old Lovable site)

- Service times: Sundays 10:00 (Early Morning Altar) · Wednesdays 17:00 (Midweek Intercession) ·
  Fridays 17:00 (Night of Fire). The old site listed Sun 6–7:30am / Wed 7–9pm / Fri 8–10pm — **wrong**, per
  operator; WDF's onboarding times are what's live.
- Address: FL 10 Itlameng Street, Kagung, Kuruman — the old site had no address ("contact us for the
  current venue"). Now shown directly + on the embedded map.
- Pastor's cell: 060 459 3822 — wired as `tel:+27604593822` on the "Call the church" button.
- **Email deliberately omitted.** The old site used `hello@furnaceofprayer.org`; WDF's own record has
  `hallo@furnaceofprayer.org` (note the "hallo" — believed to be a typo on our side). Per operator
  instruction, neither is published until Nosipho confirms the correct address with the pastor. Add it to
  the footer/times section once confirmed.

## Images — this church is the exception to the usual stock-photo pipeline

The old site's only non-logo image was a generic vector flame graphic reused twice — exactly the kind of
generic stock that makes WDF sites look templated. Per operator instruction:

- Removed all 5 v1 generic Pexels "people" photos (choir, praying man, community outreach, mismatched
  Christmas-themed bible/candle photo, and a duplicate embers shot). See git history for what they were.
- Kept **one** real photographic image, `hero.jpg` (genuine macro photo of burning coals/altar embers, not
  a vector graphic) — reused thoughtfully as the hero background and, at low opacity, behind the Visit CTA.
- Self-hosted the church's **real logo**, cropped from the operator's screenshots and made transparent:
  `logo-full.png` (full wordmark) and `logo-icon.png` (icon only, used in nav/footer/favicon). These are
  screenshot crops, not source art — swap for a clean export if the pastor has the original file.
- The rest of the fire theme is carried by typography, colour and layout (gradient headlines, the ember
  canvas animation, the pinned Leviticus 6:13 moment) rather than more stock photography.

## Still open

- Confirm the real contact email with the pastor (Nosipho) and add it once known.
- If the pastor can supply a clean/vector logo file, replace the screenshot-cropped `logo-*.png` assets.
