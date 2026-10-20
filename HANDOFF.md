# MDE Polishing Inc. — handoff at ~60% (calm-style revamp)

**Live:** https://10elizabethbell.github.io/mdePolishing/ · **Repo:** https://github.com/10elizabethbell/mdePolishing · **Built:** 2026-10-17 from Muse brief (run 2026-10-17, Essex County Contractor Referrals post) · **Revamped:** 2026-10-19 into the calm band style

## What changed in the revamp (2026-10-19)
The business hasn't been contacted, so the whole page was rebuilt from DPG's calm-style `index.html` under the new house rules. Facts, photos and contact wiring carried over; the look, structure and motion are new.
- **Gone:** the polished-concrete floor drawn under the whole page, the scroll-driven light reflections, the epoxy-pour band edges that bulged from the finger, saw-cut joints, heavy uppercase system type, outlined buttons. All of it is in git history (`ae90afd`) if Ellie wants any of it back as the opt-in signature.
- **New look:** paper (#f4f6fb), logo blue deepened to #1d3cc4 (services/quote band), logo navy #14215a with the faint diagonal texture (How it works, footer), one warm accent: grinder amber #f2a51a as a fill (navy text on it; #8a5a00 when it has to be text on light). Cal Sans headings, system body 16/1.7, 24px cards, pill buttons, 10px fields on their own #e6ecf5 fill.
- **New hero:** their own job photo (the grinder mid-job, from the room pair) under a navy overlay; white text measures 6.3:1 or better by pixel sampling at 360, 390 and 1440. Eyebrow pill with their logo tagline, H1 "Floors that shine in Essex County" (bounces in letter by letter, then restores the plain heading), the care promise, two pill buttons.
- **New motion:** H1 bounce-in, one 12px fade-up for things below the first screen, and the 60px floating text circle (shows after the hero, hides over the form). Reduced motion and no-JS show everything at once.
- **Structure now:** header (logo, 226-808-4556 top right) → hero → What we do (six rows) → How a quote works (3 steps) → Before and after (two pairs, then the Facebook link) → Get a quote (form on the blue band) → close (name, big number) → footer (© line, Facebook).
- **Form:** job chips now match all six services (plus "Not sure yet"); floor type is optional; name and town required. Phones open Messages; desktop shows the message with Open in Messages / Copy message and the number as plain text.

## What's built
- Phone first: first 390px screen shows logo, number, what they do, the headline and both buttons.
- **Contact:** hero "Text us photos of your floor" and the floating circle open `sms:` with a pre-written photos message. Each service row texts about that service on phones. On desktop (no Messages app) the hero button and circle jump to the form, and a row jumps there with that job ticked. Calling is the header number and the close's big number (one per screen).
- **Proof:** the two before/after pairs, as shot (3:4), labels Before/After only, then "Click to see more of our work on Facebook".
- og image re-rendered from the new hero (`assets/og.jpg`); favicon and apple-touch icon unchanged (from the logo).

## Assumptions I made
- **"Essex County" in the H1.** The brief says area unknown; the only evidence is that they posted in the Essex County Contractor Referrals group and the 226 area code. The calm style needs the place in the H1, so I used it. Confirm with the owner, or swap for their real towns.
- **Amber accent.** The logo has no warm colour. Amber comes from the orange grinders in their own photos.
- **Hero promise** ("We treat your floor like it's our own, from the first pass of the grinder to the last coat.") is tone, not a fact. Same for steps 2–3 ("We tell you straight", "Proper prep comes first…").
- **Voice "we":** it's an Inc.; crew size unknown.
- **Texting is the main path, but the brief says "accepts texts: unknown".** Calling stays one tap away in the header and close.
- The hero photo is also the "Before" in the first pair (different crop). It was the only photo that reads as their trade at a glance and survives the wide desktop band.

## Placeholders and gaps
- Service area (towns), email (footer has none), hours, owner name, reviews, prices, years in business, insurance.
- Only two before/after pairs; neither is shot from the same spot, so no sliders.

## Questions for the owner
- Do you take texts at 226-808-4556?
- Which towns do you cover? Is "Essex County" right?
- An email for the footer?
- More before/after pairs (garage epoxy, polished floors), ideally from the same spot?
- Your first name, so the page can speak as you?
- Which services bring in the most work (sets the row order)?
- Insured? Years doing this?

## Ideas not built (yours to pick)
- **Opt-in signature motion (runner-up worlds):** (1) the polished floor with scroll-driven light reflections from the previous build (in history at `ae90afd`); (2) metallic epoxy that swirls under the finger like a fresh pour; (3) a grinder pass that wipes dust off a slab as you scroll; (4) flake epoxy scattering onto a wet coat. Best: (1), since it's already built.
- A third hero option once a wide, bright photo of a finished floor exists (the current photo is mid-job).
- Finish swatches per service row.
- Photo-upload quote form (needs a backend such as Formspree; paid follow-up).
- **Impeccable findings kept because they're your calm-style choices:** the craft floor bans eyebrows outright (all three here are quiet `<p>` pills; "Our work" above "Before and after" adds little, so swap the word or drop that one if you like); "one authored moment" vs the bounce-in plus fade-up; the detector's repeating-stripes flag on the band texture (suppressed in `.impeccable/config.json` with your rule as the reason); "flat type hierarchy" (counts only the 14–21px body/label sizes; left standing).
- **Self-host Cal Sans** (reviewer, optimize): the Google Fonts stylesheet blocks render on slow cellular, and if the font swaps in mid bounce-in the letters jump. A preloaded local `CalSans.woff2` fixes both, but the house rule names Google Fonts, so it's your call.
- A sharper desktop hero needs a bigger original; the crop is 1316px wide (about 2.2x upscale on a 1440 retina screen, softened by the overlay).

## Impeccable sweep applied (2026-10-19)
Finish reviewer covering critique, audit, polish, harden, clarify, adapt, optimize, typeset, layout, colorize, quieter/bolder, distill, delight, animate (live skipped: needs you in the browser; onboard n/a). Applied: desktop hero button and floating circle go to the form instead of a dead `sms:`; the desktop "sent" panel says "Copy this and text it…" with only a Copy button (no second amber "open" button) and the "Opens your messages" note hides after sending; the hidden float is no longer a tab stop; the logo link scrolls to the very top so the header number stays; footer name became a small © line (the close already shows the name); "How a quote works" lost its stray period; step titles are `<h3>`; Before/After labels hidden from screen readers (the alt text says it); the submit label fits on one line at 360px; Facebook row spans the width on desktop.

## Not verified
- Real-device touch on iPhone Safari and inside Facebook's in-app browser (Playwright WebKit stands in).
- Real `sms:` handoff with a prefilled body on iOS and Android.
- Cal Sans load time on slow cellular (headings fall back to Avenir Next / Segoe UI until it arrives; `display=swap`).
