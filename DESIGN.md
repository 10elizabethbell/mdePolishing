---
name: MDE Polishing Inc.
description: A calm, phone-first page for a concrete grinding and polishing crew. Their own grinder photo under navy, paper and navy bands, one grinder-amber accent, Cal Sans headings.
colors:
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  ink: "#14215a"
  body: "#2a3352"
  soft: "#4a5868"
  navy: "#1d3cc4"
  deep: "#14215a"
  on-dark: "#f4f6fb"
  on-dark-soft: "#d3dcf7"
  amber: "#f2a51a"
  amber-2: "#f7bb4a"
  amber-ink: "#8a5a00"
  focus: "#1d3cc4"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(44px, 12.6vw, 84px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  display-tel:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(34px, 10vw, 56px)"
    fontWeight: 400
    lineHeight: 1
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(19px, 5.2vw, 22px)"
    fontWeight: 400
    lineHeight: 1.2
  title-step:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  label-display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.15
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  body-small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
rounded:
  focus: "6px"
  field: "10px"
  panel: "16px"
  row: "20px"
  card: "24px"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-desktop: "40px"
  section: "64px"
  section-desktop: "96px"
  container: "1160px"
  card-pad: "clamp(20px, 5vw, 32px)"
components:
  button-primary:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.amber-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 20px"
    height: "48px"
  button-line-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  eyebrow:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  service-row:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    rounded: "{rounded.row}"
    padding: "10px 12px 10px 22px"
    height: "68px"
  facebook-row:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    rounded: "{rounded.row}"
    padding: "14px 16px 14px 22px"
    height: "76px"
  step-numeral:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  shot-card:
    backgroundColor: "{colors.field}"
    textColor: "{colors.card}"
    rounded: "{rounded.card}"
  form-card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.body}"
    rounded: "{rounded.card}"
    padding: "{spacing.card-pad}"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  sent-panel:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.body}"
    rounded: "{rounded.panel}"
    padding: "18px"
  float-circle:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: MDE Polishing Inc.

## Overview

**Creative North Star: "The Calm Crew Sheet"**

Calm order gets trust before any claim does. The page is a stack of full-bleed bands that switch between light and dark, so every new section is easy to spot: the crew's own grinder photo under a navy wash, paper for the services, deep navy for how a quote works, paper for real before/afters, logo blue for the quote form, paper for the closing phone number, deep navy for the footer. Each band does one thing. Shapes are soft and have no borders: 24px cards, 20px rows and full pills. The page reads like a tidy job sheet from a crew that preps properly.

Colour comes from the logo. Its royal blue is deepened so white text sits on it, and its tagline navy is used twice: for the text and for the darkest bands. Grinder amber, taken from the orange machines in their own photos, is the one warm note and is always a fill. Headings are Cal Sans at weight 400 and carry the whole hierarchy. Body text is the system stack at 16/1.7 and stays quiet. The page is phone-first and works in one column, with two columns for rows and photo pairs from 760px up.

Motion stays small. The hero H1 bounces in letter by letter once. Anything that starts below the first screen fades up 12px. A single amber text circle slides in once the hero has scrolled away. With JS off or reduced motion on, every item is visible at rest and the heading is plain.

**Key Characteristics:**
- Full-bleed bands that alternate light and dark, in a fixed order, with a faint diagonal line texture on deep navy only
- Logo blue (#1d3cc4) and tagline navy (#14215a) as the band colours; grinder amber as the single fill accent
- Cal Sans 400 for every heading, button, row and label; system stack for running text
- Borderless soft shapes: 24px cards, 20px rows, 10px fields, full pills
- One real job photo in the hero, real before/after photos below, no stock or illustration
- One-shot H1 bounce-in, a 12px fade-up only below the first screen, and one floating text circle

## Colors

Paper and two navies, with one grinder-amber accent that is always a fill and never a text colour on light.

### Primary
- **Logo Blue** (navy): the mid band behind the quote form, and the colour of the Facebook mark. It also serves as the hover colour for the header and closing phone numbers. It is the logo's royal blue deepened until white text passes on it.
- **Form Focus Blue** (focus): the same hue used as the hover and focus outline for form controls on the white form card, kept apart from the amber fill so focus never looks like a selection.

### Secondary
- **Tagline Navy** (deep): the hero base under the photo, the how-it-works band and the footer, always with the diagonal texture on the bands. It shares its hex with Ink because the logo uses one navy for both jobs.

### Tertiary
- **Grinder Amber** (amber): fills only. The primary button, the step numeral discs, the floating circle, a service row's arrow disc on hover, the eyebrow dot, text selection, focus outlines on dark bands, and the accent phrase in headings on dark bands.
- **Lit Amber** (amber-2): the primary button's hover fill.
- **Amber Ink** (amber-ink): amber as a text colour on light, at 5.5:1. Used for the phone icons in the white header and on the paper close band; it is also the `.accent` colour on paper.

### Neutral
- **Paper** (paper): the page ground and the light bands, plus the sent-message panel inside the form.
- **Card White** (card): the header, service and Facebook rows, the form card, and white text on photos and selected chips.
- **Field Tint** (field): fill for inputs and chips on the white form card, and the placeholder colour behind loading photos. It is its own token because paper on white is about 1.08:1 and fails as a control boundary.
- **Ink** (ink): headings and strong text on light, and text on amber.
- **Body** (body): running text on light.
- **Soft** (soft): ledes, hints, placeholders and secondary lines on light.
- **On-Dark** (on-dark): headings and the ghost button on navy and deep bands.
- **On-Dark Soft** (on-dark-soft): running text on navy and deep bands, and in the footer.
- **Error Red** (error): inline error sentences and the invalid field border.

### Named Rules
**The Amber Is a Fill Rule.** Amber never carries text on a light ground; text on amber is always Ink. When amber has to be text on paper or white, use Amber Ink.

**The Accent-Phrase-on-Dark Rule.** A heading's last phrase may switch to amber only on a dark band or the hero ("Essex County", "works", "quote"). Paper headings stay Ink all the way through.

**The Logo Colours Only Rule.** The blues and navies come from the logo, and the amber comes from their own grinders. Don't add another hue.

## Typography

**Display Font:** Cal Sans (Google Fonts, `display=swap`, preconnected), with Avenir Next, Segoe UI, system-ui fallback
**Body Font:** System stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** A rounded, friendly geometric display face at one weight (400) does all the talking. It sets headings, buttons, service rows, form labels, phone numbers and step numerals. The system body stays neutral, so the display face is the only voice.

### Hierarchy
- **Display** (400, clamp(44px, 12.6vw, 84px), 1.02, max 11ch): the hero H1 only, set in white on the photo.
- **Display Tel** (400, clamp(34px, 10vw, 56px), 1): the closing tap-to-call number, with a 0.75em amber-ink phone icon.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08, balanced wrap): every section H2.
- **Title** (400, clamp(19px, 5.2vw, 22px), 1.2): service row and Facebook row labels. Photo tags use the same face at clamp(18px, 5vw, 22px)/1 in white.
- **Title Step** (400, 21px, rising to 22px at 1024px, 1.2): how-it-works step titles (h3).
- **Label Display** (400, 17px, 1.2): form labels and legends. The header phone number uses the display face at 17px, or 21px on desktop. Step numerals use it at 20px.
- **Button** (400, 18px, 1.15): all buttons. Buttons in the sent panel drop to 16px.
- **Promise** (system, clamp(17px, 4.7vw, 20px), 1.5, 32ch, or 40ch on desktop): the hero's single care line.
- **Lede** (system, clamp(17px, 4.6vw, 19px), max 38ch): a section intro under a headline.
- **Body** (system, 16px, 1.7): running text, step descriptions (36ch), inputs and chips. Inputs never go below 16px, so iOS doesn't zoom.
- **Body Small** (system, 15px, 1.5): inline errors, the "opens your messages" note and the composed message preview.
- **Label** (system 500, 14px, 1, +0.02em): eyebrow pills, plus the "(optional)" hints and the footer copyright at weight 400.

### Named Rules
**The One Display Weight Rule.** Cal Sans is only ever used at 400. Hierarchy comes from size, never from bold.

**The Display Carries Hierarchy Rule.** Body and label sizes stay deliberately close together (14–20px). The ramp lives in the display scale (84 / 56 / 48 / 22px). A detector reading this as a flat hierarchy is looking only at the body tier, and that flatness is intentional.

## Layout

A single centred container (1160px max) with a 20px gutter on phones and 40px from 760px up. Bands run full-bleed with 64px vertical padding, or 96px on desktop. The hero copy pads 56/64px on phones and 112/120px on desktop, over a photo set to `object-fit: cover` (focal point 50% 55%, or 62% from 1024px).

- **Phones (default):** one column. Hero buttons stack full width. Service rows, photo pairs and steps stack.
- **760px and up:** service rows and the two before/after pairs go to two columns (pair gap 24px). Hero buttons sit side by side, each at least 220px wide.
- **1024px and up:** the quote band splits 1fr / 1.25fr with a 64px gap, and its heading block sticks at 40px from the top. Steps go to three columns with a 40px gap. The close band places the name block and the big phone number on one row, aligned to the bottom.
- **380px and down:** chip and submit padding tighten.

Rhythm inside bands is a short run of gaps: 10–12px between siblings, 16–24px within groups, 28–36px between a headline and its content. Text measures are capped (11ch for H1, 32–40ch for the promise, 38ch for ledes, 36ch for steps). The form card stays at 620px or narrower.

### Named Rules
**The Fixed Band Order Rule.** Hero photo under navy, then paper services, deep how-it-works, paper before/after with the Facebook row, navy quote form, paper close, deep footer. Light and dark alternate, so a new section is always obvious. Don't put two dark bands next to each other.

## Elevation & Depth

The system is flat. Depth comes from band colour and from white cards sitting on paper or navy, not from shadows. Rows and cards have no shadow at rest or on hover. There are only two layered effects. The hero photo sits under a vertical navy gradient (80% → 72% → 88% opacity of Tagline Navy), which keeps white text at 4.5:1 or better while the grinder stays readable. Photo cards carry a bottom 40% gradient from transparent to 78% navy, so their white tag reads.

### Shadow Vocabulary
- **Float lift** (`box-shadow: 0 10px 28px rgba(10,18,52,.3)`): the floating text circle only, because it is the one element above the page.

### Named Rules
**The Only the Float Floats Rule.** Nothing but the fixed text circle casts a shadow. Hover never adds one.

**The Faint Texture Rule.** Deep navy bands (how-it-works, footer) carry `repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`. Keep it at about 4% white or fainter so it never reads as lines through the text. Use it only on deep navy, never on paper or Logo Blue. This is an intentional house-style exception to the striped-gradient detector rule.

## Shapes

Soft and borderless. Containers are rounded rectangles with no stroke. The radius steps down with the size of the element: 24px for photo cards and the form card, 20px for service and Facebook rows, 16px for the sent panel inside the form, and 10px for inputs. Every button, chip and eyebrow is a full pill, and every round marker (arrow discs, step numerals, the float, the eyebrow dot) is a true circle. Focus rings get a 6px radius. Photos are clipped to their card radius and never stretched. Before/after shots are 3:4.

## Components

### Buttons
Big, soft pills set in the display face. They feel tactile: a press shrinks them slightly.
- **Shape:** full pill (999px), at least 56px tall, 26px side padding, 2px border, an optional 20px leading icon.
- **Primary:** Grinder Amber fill and border with Ink text. Used for "Text us photos of your floor", the form submit (full width) and the sent panel's main action.
- **Hover / Focus:** primary moves to Lit Amber. Every button scales to 0.98 on `:active`, with 0.2s colour transitions. Hover styles apply only under `(hover:hover)`. Inside the form, hover and focus add a 2px Form Focus Blue outline at 2px offset.
- **Ghost:** transparent, On-Dark text and a 70% On-Dark border, used on the hero only. On hover the border goes fully white over a 10% white wash.
- **Line:** transparent, with Ink text and an Ink border. It fills with Ink and turns white on hover. Used for "Copy message" in the sent panel at 48px tall and 16px type.

### Eyebrow (intentional exception)
- **Style:** a small pill set at system 500, 14px, +0.02em. It has a 7px amber dot, 9px/14px padding and a 6% ink tint on paper, or On-Dark text on a 12% white tint on the hero and dark bands.
- **Use:** above three headings only: the hero ("Concrete grinding and polishing", the company tagline), "Our work" and "Photos help". It is marked up as a `<p>`, never a heading. It has no arrow, no hover, no shadow and no full-strength fill, so it can't be mistaken for a button.
- **Status:** Ellie's house rule (calm-photo-style, 2026-10-19) overrides the craft-floor ban on eyebrows. Use it on a few key headings only, not as a label on every section.

### Chips
- **Style:** a Field Tint pill, 48px tall with 18px padding, 16px system text in Ink and a 2px transparent border. The native checkbox or radio is visually hidden behind the label.
- **State:** selected becomes an Ink fill with white text. Hover gives a Form Focus Blue border. Keyboard focus adds a Form Focus Blue border plus a 3px outline at 3px offset, so focus stays visible on the selected Ink fill.

### Cards / Containers
- **Corner Style:** 24px (form card, photo cards), 16px (sent panel).
- **Background:** Card White for the form on Logo Blue, Paper for the sent panel inside it, and Field Tint behind photos while they load.
- **Shadow Strategy:** none (see Elevation & Depth).
- **Border:** none.
- **Internal Padding:** form clamp(20px, 5vw, 32px) with 22px between fields. Sent panel 18px.

### Inputs / Fields
- **Style:** Field Tint fill, a 2px transparent border, 10px radius, 52px minimum height (textarea 110px, resizes vertically), 16px system text in Ink with a Logo Blue caret. Placeholders use Soft. Labels sit above in the 17px display face, with "(optional)" hints in 14px Soft.
- **Focus:** the border turns Form Focus Blue (0.15s), with no outline ring. Hover does the same on pointer devices.
- **Error:** a plain-sentence message in 15px Error Red appears under the field, and the border turns Error Red. A later, more specific rule keeps the red border while the field is focused.

### Navigation
- **Header:** a white bar, 68px tall on phones and 84px on desktop, with no shadow. The real logo sits left (52px, or 64px on desktop) and links to the top. The tap-to-call number sits right in the display face (17px, or 21px on desktop), with an 18px amber-ink phone icon. The number turns Logo Blue on hover. The header is the only top navigation. There is no menu.
- **Footer:** deep navy with the texture. It holds 14px copyright and underlined On-Dark links (Facebook) at least 44px tall, with the underline at 40% On-Dark and 4px offset. Links turn amber on hover. Bottom padding leaves room for the float.

### Service Row (signature)
Each of the six services is a whole-row link that texts about that job (on desktop it opens the quote form with that chip ticked). A Card White rounded row (20px radius, at least 68px tall) holds the service name in the Title display size and a 44px arrow disc at the right on a 7% ink tint. **Only the arrow changes:** on hover the disc fills Grinder Amber. On keyboard focus the disc fills amber and takes a 3px Form Focus Blue outline at 3px offset, while the row's own outline and background stay put. Rows sit one per line on phones and two per line from 760px.

### Facebook Row
The same row anatomy as a service row, made larger (76px, 14px/16px padding). It has a 30px Facebook mark in Logo Blue, then "Click to see more of our work on Facebook", then the same arrow disc. Hover and focus behave exactly like the service row. It closes the before/after band.

### Steps
A numbered list on deep navy. Each step has a 48px Grinder Amber disc with an Ink numeral (Cal Sans 20px, from a CSS counter) and a 16px gap to its text. The title is an h3 in Title Step size in On-Dark, followed by a 36ch On-Dark Soft description. Steps stack with a 24px gap on phones and sit in three columns at 1024px.

### Shot Card (Before / After)
A pair of real job photos side by side (10px gap), each a 3:4 figure clipped to 24px. A bottom navy gradient sits under a white "Before"/"After" tag at bottom-left (16px/12px inset). The tag repeats what the alt text already says, so it is aria-hidden. There is no caption and no arrow.

### Sent Panel
After submit, a Paper panel (16px radius, 18px padding) appears inside the form as a `role="status"` region. It shows a bold Ink line, the composed message in 15px pre-wrapped body text, and pill buttons (48px). On phones the main action is "Open in Messages" and the Line button is "Copy message". On desktop, where nothing opens, only "Copy message" shows, promoted to Primary. The Ink-coloured number stays as a plain fallback.

### Close Phone Number
The closing band ends on the business name (headline), a soft one-line description and the number itself in Display Tel size, Ink, with an amber-ink phone icon. It turns Logo Blue on hover. On desktop it sits bottom-right of the name block.

### Floating Text Circle
One 60px Grinder Amber circle with a 26px Ink chat icon, fixed 16px from the bottom-right corner (inside the safe area), and the only shadowed element. It stays hidden (translated 120px down, `visibility:hidden`, `tabIndex=-1`, `aria-hidden`) until the hero has scrolled away. It hides again while the quote form is on screen, so two controls that do the same thing are never in view together. It slides in over 0.35s `cubic-bezier(.2,.8,.2,1)`. On phones it opens a pre-filled `sms:`. On desktop it links to the form. Without IntersectionObserver it is removed. It is always one circle, never a bottom bar.

### Motion and Reduced Motion
- **H1 bounce-in (hero only):** JS splits the H1 into letter spans inside `white-space:nowrap` word wrappers, keeping the `.accent` span. Each letter runs from `opacity:0; translateX(50px)` to rest over `1s cubic-bezier(.34,1.56,.64,1)`, 20ms apart. The H1 gets an `aria-label` and the letter wrappers are `aria-hidden`. When the last letter's `animationend` fires, the original HTML comes back, which restores kerning and text selection.
- **Fade-up:** elements marked `.rise` that start below the first screen get a `.below` class (12px down, opacity 0). They rise over 400ms ease-out as they enter (IntersectionObserver, -8% bottom margin). Anything already on screen is never hidden.
- **Reduced motion / no JS:** no split, no hidden content, no float slide and no button transitions. A CSS backstop forces the letters visible. Smooth scrolling turns off.

## Do's and Don'ts

### Do:
- **Do** keep the band order: photo hero under navy, paper, deep, paper, navy form, paper close, deep footer.
- **Do** use Grinder Amber as a fill with Ink text on it, and Amber Ink (#8a5a00) whenever amber has to be text on light.
- **Do** set every heading, button, row label and form label in Cal Sans at 400, and running text in the system stack at 16/1.7.
- **Do** put inputs and chips on Field Tint (#e6ecf5), not Paper, when they sit on the white form card.
- **Do** keep service and Facebook rows still on hover: only the 44px arrow disc fills amber.
- **Do** use focus outlines that show on their ground: 3px amber on dark bands and the hero, 3px Form Focus Blue (#1d3cc4) at 3px offset on light and inside the form.
- **Do** keep everything visible at rest. Hide only `.rise` elements that start below the first screen, and only when JS is on and reduced motion is off.
- **Do** keep tap targets at 44px or more (buttons 56px, chips 48px, rows 68px).
- **Do** keep eyebrows to a few key headings, quiet (14px, tinted, amber dot), and marked up as `<p>`.

### Don't:
- **Don't** add shadows to cards, rows or the header. The floating circle is the only element that casts one.
- **Don't** set amber text on paper or white, or white text on amber.
- **Don't** apply the letter bounce-in to any heading other than the hero H1, or add other entrance effects.
- **Don't** put the diagonal texture on paper or Logo Blue bands, or make it stronger than about 4% white.
- **Don't** turn the floating circle into a bottom bar, or show it while the form is in view.
- **Don't** give an eyebrow an arrow, hover state, shadow or full amber fill, and don't add one to every section.
- **Don't** add a Call button to the hero. The number lives in the header and the close band.
- **Don't** use stock or illustrated imagery. Every photo is the crew's own job, cropped with `object-fit: cover` and never stretched.
- **Don't** set Cal Sans in bold.
