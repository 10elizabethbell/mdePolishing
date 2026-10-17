# MDE Polishing Inc. — handoff at ~60%

**Live:** https://10elizabethbell.github.io/mdePolishing/ · **Repo:** https://github.com/10elizabethbell/mdePolishing · **Built:** 2026-10-17 from Muse brief (run 2026-10-17, Essex County Contractor Referrals post)

## What's built
- One page, phone first: header (real logo + `226-808-4556` top-right), hero, What we do, How a quote works, Facebook proof band, quote form, close, footer.
- **World:** the polishing floor. Light concrete-grey ground taken from the logo's background, logo blue `#2c54f7` and navy `#14215a`, buttons outlined in navy-black like the logo's outlined letters. Section edges are slow-flowing epoxy pours that bulge away from the pointer or finger.
- **Signature:** the hero slab is a matte, trowel-marked concrete floor with cracks and an oil stain. A blue walk-behind grinder (handlebar, control box, vacuum hose) polishes it on autopilot down to salt-and-pepper aggregate, with the shop's light tubes reflecting in the gloss. Mouse or finger takes over, dragging in any direction, including up and down on phones. It returns to autopilot after 2.6s idle, and the polish slowly dulls back so there's always floor left to do. Tunables are at the top of the hero IIFE.
- **Contact:** the hero button "Text us photos of your floor" opens `sms:` with a pre-written message. Each service row texts about that service on phones; on desktop it jumps to the form with the service ticked. The form writes the text message: on phones it opens the text app, on desktop it shows the message with a Copy button. Calling uses the header number, plus "or call" in the close section.
- **Verified:** Chromium and WebKit at 360/390/430/1440: no sideways scroll, tap targets ≥44px, inputs 17px, primary button on the first screen. A touch sweep polishes without scrolling the page. Form errors and the composed text decode correctly. The detector is clean apart from two suppressed false positives and one accepted note (below).

## Assumptions I made
- **Voice "we":** it's an Inc. Crew size unknown.
- **Colors:** sampled from the Facebook profile logo. No other brand material exists.
- **Hero promise** ("We take a tired, stained floor down to fresh stone…"): describes what grinding and polishing does, not a claim about this owner. The reviewer suggested an alternative: "We treat your floor like it's our own, from the first pass of the grinder to the last coat."
- **"How a quote works" steps 2–3** ("We tell you straight… sometimes a grind and seal does the job for less", "the part we don't rush") are tone, not facts. Confirm the owner is OK with them.
- **Customers** (garages, basements, shops) are inferred from the services list. Form floor types follow from that.
- **Texting is the main path, but the brief says "accepts texts: unknown".** Calling stays one tap away in the header and close. Confirm with the owner before pitching.
- **Phone number:** removed from the footer because it would sit on the same phone screen as the close section's "or call" line (once-per-screen rule).

## Placeholders and gaps
- **No work photos.** The Facebook post image was the group's stock cover photo (a model house on blueprints), so it isn't used. The proof band is just a big Facebook link.
- **Service area:** unknown. The 226 area code says southwestern Ontario and the post was in an Essex County group, but no towns appear on the page.
- No email (footer has none), hours, owner name, reviews, prices, years in business, insurance or certifications.
- **Favicon:** drawn as "MDE" in the logo's blue and outline style. The apple-touch icon is the logo's stacked MDE mark cropped from the profile picture (720px source).
- **og image** (`assets/og.jpg`): a render of the desktop hero.

## Questions for the owner
- Do you take texts at 226-808-4556? (The whole quote flow leans on it.)
- Which towns do you cover? (Windsor–Essex? Chatham-Kent? London?)
- Can we have 6–10 photos of finished floors, ideally before/after pairs from the same spot? These would replace the Facebook-only proof band.
- Your first name, so the page can speak as you?
- Which services bring in the most work (epoxy garages vs polished commercial)? That would set the service order.
- Insured? Years doing this? Any product lines you use (metallic epoxy, flake systems)?
- An email for the footer?

## Ideas not built (yours to pick)
- **Runner-up world:** metallic epoxy pour. Marbled blue/navy metallic epoxy that swirls under the finger like a fresh pour. Would carry the logo blue harder.
- Finish swatches for each service row (polished, flake epoxy, metallic, sealed wet-look, peeled coating), drawn live in canvas.
- Before/after sliders once the owner sends pairs (house recipe in `ellie-taste.md` §4).
- A stain-gone moment: make the oil stain stronger so grinding over it visibly removes it.
- A garage-door "reveal" for the close section.
- A photo-upload form is impossible without a backend. Texting photos is the honest equivalent; a hosted upload (e.g. Formspree) is possible later as paid work.

## Not verified
- Real-device touch on iPhone Safari and inside Facebook's in-app browser (WebKit via Playwright stands in).
- Real `sms:` handoff with a prefilled body on iOS and Android.
- Frame rate on old phones (desktop ~110fps; the canvas is capped at 1.5x DPR).
- Older iOS without `roundRect` (falls back to plain rects).
- Detector note left standing: "flat type hierarchy" counts the 14–22px body/label sizes. The display scale (h1 up to 96px, h2 up to 58px) carries the hierarchy.
- Impeccable concept-roll seed: skipped. The pitch-site pipeline chooses the world unattended.
