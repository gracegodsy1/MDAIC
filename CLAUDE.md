# Metro Denver Accident & Injury Centers — Landing Page

## What this project is
A single-page marketing landing page for **Metro Denver Accident & Injury Centers (MDAIC)**,
a chiropractic / auto-accident-injury clinic with two Colorado offices. Built from the client's
existing Wix site: https://gracegodsydc.wixsite.com/metrodenver

**Primary file:** `MDAIC Landing.dc.html` (a Design Component — edit via dc_* tools).
`MDAIC-Landing.html` is a bundled, self-contained export for GitHub/hosting — regenerate it with
super_inline_html after any change; never edit it directly.

## Business facts (keep accurate)
- **Founded:** 1992. Tagline: "Raising the standard in accident and injury care."
- **Westminster office:** 680 W 121st Ave, Suite 100, Westminster, CO 80234 · 303-457-4570 · frontdesk@metrodenveraccident.com
- **Aurora office:** 1444 S Potomac St. #170, Aurora, CO 80012 · 303-927-7027 · metrodenveraurora@gmail.com
- **Doctors:**
  - Dr. Christopher Higgins, D.C. — Founder; Chiropractic Physician
  - Dr. Paul Endriss, D.C. — Owner; Chiropractic Physician (MDAIC Aurora)
  - Dr. Grace Godsy, D.C. — Chiropractic Physician (MDAIC Westminster)
- **Scheduling portal:** https://practice.chirotouch.com/portal/MetroDenverAccidentandInjury

## Page sections (top → bottom)
Top contact bar · sticky nav (logo slot + HOME/ABOUT/SERVICES/CONTACT + Schedule Now) ·
hero · about/intro · **Services** (Conditions We Treat → Our Treatments → New Patient Evaluation) ·
team (3 doctors) · contact form · reviews · footer (both locations).

## Design system
- **Palette:** deep green `#14332f` (dark sections/footer `#0f2723`), warm off-white `#f6f4ef`,
  muted stone `#eeeae1`, amber/terracotta accent `#b8763a` (hover `#a3652f`), body text `#1e2422`/`#4f5852`.
- **Type:** `Newsreader` (serif) for headings, `Libre Franklin` (sans) for body/labels/nav.
  Section eyebrows are uppercase amber, 0.2em letter-spacing, 700 weight.
- **Style:** editorial, calm, trustworthy medical. No gradients, no emoji, minimal rounding (2–4px).
  Striped repeating-linear-gradient placeholders stand in for photos not yet supplied.

## Images
- Logo lives in `<image-slot>` elements (nav + footer) — drag-and-drop, persists in localStorage.
- `logo-footer-light.png` is a background-removed, lightened logo for the dark footer.
- All photo placeholders are labeled slots/striped boxes awaiting real client photos
  (hero, treatment room, 3 doctor headshots, 3 condition images, 6 treatment images).

## Conventions
- Inline styles only (Design Component rule). Spacing uses flex/grid + gap.
- Keep the two-office structure everywhere; don't collapse to one location.
- Reviews are generic placeholders (real site uses a Google Reviews widget).
