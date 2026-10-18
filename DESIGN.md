---
name: MDE Polishing Inc.
description: A raw, dusty slab becomes a floor you can see yourself in. One phone-first page in logo blue and navy on polished salt-and-pepper concrete.
colors:
  ground: "#aeaca7"
  ink: "#0d1636"
  ink-soft: "#1f2643"
  blue: "#2c54f7"
  blue-deep: "#1d3cc4"
  navy: "#14215a"
  on-navy: "#eef0fa"
  on-navy-soft: "#b9c0e0"
  line: "rgba(13,22,54,.3)"
  focus: "#f0a51c"
  paper: "#ffffff"
  error: "#7d1610"
typography:
  display:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.75rem, 13.4vw, 5.6rem)"
    fontWeight: 900
    lineHeight: 0.9
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem, 9vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.015em"
  title:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "-0.015em"
  row:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.125rem, 5vw, 1.5rem)"
    fontWeight: 800
    lineHeight: 1.55
    letterSpacing: "0.01em"
  body:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.55
  lede:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 800
    lineHeight: 1.55
  button:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 800
    lineHeight: 1.1
rounded:
  field: "12px"
  card: "14px"
  pill: "999px"
  round: "50%"
spacing:
  chip-gap: "8px"
  action-gap: "10px"
  form-gap: "22px"
  gutter: "20px"
  gutter-wide: "40px"
  band: "56px"
  band-wide: "96px"
  column-gap: "60px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.blue}"
    textColor: "{colors.paper}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 1.4em"
    height: "58px"
  button-primary-hover:
    backgroundColor: "{colors.blue-deep}"
    textColor: "{colors.paper}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 1.4em"
    height: "58px"
  button-ghost-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.row}"
    padding: "10px 2px"
    height: "66px"
  service-row-arrow:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.round}"
    size: "44px"
  service-row-arrow-hover:
    backgroundColor: "{colors.blue}"
    textColor: "{colors.paper}"
  input-text:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "13px 15px"
    height: "54px"
  chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
  before-after:
    backgroundColor: "#3a3f55"
    rounded: "{rounded.card}"
  before-after-tag:
    backgroundColor: "rgba(13,22,54,.72)"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    padding: "4px 10px"
  before-after-knob:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.navy}"
    rounded: "{rounded.round}"
    size: "44px"
  link-card-on-navy:
    backgroundColor: "rgba(255,255,255,.06)"
    textColor: "{colors.paper}"
    rounded: "{rounded.card}"
    padding: "18px 20px"
  phone-link:
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    height: "44px"
---

# Design System: MDE Polishing Inc.

## Overview

**Creative North Star: "The Polishing Floor"**

The page is a polished concrete shop floor under shop lights. Its ground is salt-and-pepper concrete, ground flat and honed: a warm mid-grey cement with fine grain, soft mottling and small cut aggregate chips, tiled seamlessly under the whole page and scrolling with it. The shop's light tubes reflect in it, and the reflections drift at a slower rate than the floor as you scroll, the way real reflections slide across a gloss. Its voice is a heavy, uppercase sans set tight like stencilled trade lettering; its colour is the logo's royal blue (the grinder) and tagline navy (epoxy). The hero is copy only, standing directly on that floor: the page itself is the finished slab, and its living elements are the drifting light reflections, the rolling epoxy-pour edges and the before/after sliders. All of it is calm and built to get a phone visitor to send a text.

Density is low and phone-first: one column, big touch targets (44px floor, 58px buttons), generous bands between sections. The light sections are one continuous floor, divided only by saw-cut control joints. Navy bands are epoxy poured over that floor: opaque, and edged by slow, rolling pour lines that swell away from a nearby finger. Depth comes from the floor's own reflections and the navy pours, not from cards and shadows.

Rejections confirmed by the build and the direction contract: no black grounds (navy carries the dark bands), no sticky header or bottom bar, no email anywhere, no stock imagery (the before/after photos are the company's own jobs).

**Key Characteristics:**
- Polished salt-and-pepper concrete under the whole page, with drifting shop-light reflections.
- Navy epoxy bands for depth, logo blue as the single action colour.
- Uppercase, weight 900, negative-tracked headings in the system sans (owner preference).
- Outlined pill buttons echoing the logo's outlined letters.
- A copy-only hero (headline, promise, two buttons) standing directly on the floor.
- Saw-cut joints between floor sections; animated epoxy-pour edges where floor meets navy.
- Drag-to-compare before/after photos of real jobs.
- Phone number is the only header element besides the logo.

## Colors

Two logo blues and a navy on polished concrete, with one warm amber reserved for hands-on feedback.

### Primary
- **Grinder Blue** (`blue`): the logo's royal blue. Primary button fill, the phone icon, the service-row arrow on hover, the default focus outline, text selection. It is the colour of the machine; it means "act".
- **Pressed Blue** (`blue-deep`): hover state of the primary button and the header phone link, and the accent word in the hero headline, where it carries blue type on the concrete at a legible contrast.

### Secondary
- **Tagline Navy** (`navy`): full-bleed, opaque epoxy bands (work, close, footer) and the fill of every pour edge. Carries a soft internal glow (a blue radial at 35% and a darker radial, masked to fade at top and bottom) so the band reads as poured, not painted. Also the colour of the icon inside white discs (Facebook card, slider knob).

### Tertiary
- **Warning-Light Amber** (`focus`): named for a grinder's warning light. Used only as the outline on hands-on controls: form controls on hover and focus, and the before/after knob on keyboard focus. Nowhere else.

### Neutral
- **Polished Concrete** (`ground`): the floor's base cement tone, the colour the floor tile is painted from, the body fallback before the tile is ready, and the `theme-color`.
- **Outline Ink** (`ink`): navy-black from the logo outline. All text on the floor, button borders, selected chip fill. Not black.
- **Soft Ink** (`ink-soft`): secondary copy (promise line, service note, step descriptions, form intro, optional-field markers). Dark enough to hold on the speckled floor.
- **Joint Line** (`line`): a translucent ink hairline so it reads on any part of the floor: rules between service rows, resting borders of inputs, chips and arrows.
- **Paper** (`paper`): input, chip and confirmation-panel surfaces; text on blue and navy; slider frames, divider and knob.
- **On-Navy** (`on-navy`) and **On-Navy Soft** (`on-navy-soft`): headings/links and body copy inside navy bands.
- **Error Red** (`error`): validation message text and the invalid input's border only; deep enough to read on the concrete.

### Named Rules
**The No Black Ground Rule.** Dark surfaces are Tagline Navy, never black or near-black. Text "black" is Outline Ink.

**The One Machine Rule.** Grinder Blue is the only colour that means "do something". Amber is feedback on hands-on controls, not a second accent.

## Typography

**Display Font:** system-ui (with -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif)
**Body Font:** the same stack
**Label/Mono Font:** none; phone numbers use tabular numerals from the same stack

**Character:** One family, pushed to its heaviest weight and set uppercase with tight tracking for headings, so it reads like stencilled trade lettering; body stays at regular weight and generous leading. The system stack is the owner's stated preference and loads instantly inside Facebook's in-app browser.

### Hierarchy
- **Display** (900, clamp(2.75rem, 13.4vw, 5.6rem) on phones, clamp(4rem, 6.4vw, 6rem) from 1024px, line-height 0.9, -0.025em, uppercase): the hero headline only. One word may be set in Pressed Blue (non-italic).
- **Headline** (900, clamp(2rem, 9vw, 3.6rem), 0.95, -0.015em, uppercase, balanced wrap): section headings, held to 12-14ch where they would otherwise run long.
- **Title** (900, 1.375rem, 1.05, uppercase): step titles.
- **Row** (800, clamp(1.125rem, 5vw, 1.5rem), +0.01em, uppercase): service-row labels.
- **Body** (400, 1.0625rem, 1.55): all running copy, held to 34-44ch.
- **Lede** (400, 1.125-1.25rem): the one-line promise and band intros.
- **Label** (800, 1rem): form labels, legends, chip text (700), the slider drag note (400), Facebook card text (800, larger).
- **Tag** (800, .8125rem, +0.04em, uppercase): the Before/After pills on the sliders.
- **Numeral** (900, 2.25rem, line-height 1, blue): step counters, drawn by CSS counters; on the concrete they follow the Pressed Blue rule for blue type.

### Named Rules
**The Heavy Caps Rule.** Every h1-h3 is uppercase, weight 900, negative tracking, line-height at or under 1.05. Body copy is never uppercase; only headings, service rows and image tags are.

**The Owner's Stack Rule.** Type is the system sans stack, by owner preference. Do not introduce a webfont; express hierarchy through weight, case and size.

## Layout

Single column on phones inside a 1180px container with 20px gutters (40px from 1024px). Sections are full-bleed bands with 56px top / 64px bottom padding, growing to 96px / 104px at 1024px. Buttons stack full-width in a 10px grid on phones and sit side by side (auto columns, left-aligned) from 600px.

The hero is copy only (headline, promise, two buttons) sitting directly on the floor, with no min-height and no grid: 10px top / 56px bottom padding on phones, a single column at 70px / 120px from 1024px.

From 1024px: services, how-it-works and the quote section become 4fr/7fr two-column grids with a 60px gap (heading left, content right); the work band stacks heading, drag note, a two-column row of before/after sliders (28px gap; 18px stacked on phones) and the Facebook card (max 520px) beneath them.

### Named Rules
**The Number Up Top Rule.** The first screen's header holds the logo left and the tap-to-call number right, nothing else. No nav menu, no sticky bar; the header scrolls away.

## Elevation & Depth

Depth is material, not stacked. The floor is one tiled surface (a 460px seamless tile drawn once in JS: cement grain, 22 soft mottling blooms, about 3,000 cut aggregate chips) set as the body background so it scrolls with the page. Behind all content, a fixed, pointer-transparent reflection layer holds rows of shop light tubes: soft white bars with a glow, one long tube or (over 900px wide) a pair per row, rows 60% of a screen height apart, each row at its own opacity. Each row is set directly from scrollY inside the scroll event (row position minus scrollY x 0.45), so they drift against the floor like real reflections in the same frame as the page; rows are recycled only while off screen. Navy bands are opaque, so reflections show only on the floor. UI itself is flat; the few DOM shadows are soft and downward.

### Shadow Vocabulary
- **Button lift** (`box-shadow: 0 6px 14px -6px rgba(13,22,54,.45)`): primary button on the floor only; removed on navy.
- **Pour shadow** (a duplicate of the pour edge path, filled `rgba(13,22,54,.13)`, offset 4px): under every epoxy-pour edge.
- **Tube glow** (`box-shadow: 0 0 22px 7px rgba(255,255,255,.3)` plus a 140px white radial wash behind each row): the reflected light tubes.
- **Saw-cut** (2px of `rgba(38,36,32,.5)` over 1px of `rgba(255,255,255,.4)`): the joint between floor sections.
- **Knob lift** (`0 2px 8px rgba(0,0,0,.4)` on the knob, `0 0 6px rgba(0,0,0,.45)` on the divider line): keeps the slider's white handle legible over any photo.

### Named Rules
**The Poured Depth Rule.** Floor meets floor at a saw-cut joint; floor meets navy at an epoxy pour. Never separate sections with a card, border box or decorative rule.

**The One Floor Rule.** Light sections have no background of their own: they are the same polished floor, and its reflections move at a different rate than the page. Under reduced motion the reflections lock to the floor (1x).

## Shapes

Round and outlined, like the logo's letters. Actions are full pills (999px) with a 2.5px Outline Ink border; small circular controls (arrows, the Facebook icon disc, the slider knob) are true circles; containers that hold content (Facebook card, before/after frames, confirmation panel) use 14px corners; text fields use 12px. Borders are thick (2-2.5px) on interactive things and framed photos, 1.5px for the service-row rules. The only straight structural line is the saw-cut joint, which belongs to the floor. The only organic shape is the pour edge: a sum of three sine waves, never a regular wave.

## Components

### Buttons
Tactile, outlined, chunky.
- **Shape:** full pill (`rounded.pill`), 2.5px Outline Ink border, minimum height 58px (48px inside the confirmation panel), 1.4em side padding, optional 22px leading SVG icon with 0.6em gap.
- **Primary:** Grinder Blue fill, Paper text, button-lift shadow. On navy bands the border turns white and the shadow drops.
- **Ghost:** transparent with Outline Ink text; fills Outline Ink with Paper text on hover.
- **Hover / Focus:** 0.2s colour transitions; primary darkens to Pressed Blue. Press nudges down 1px and scales to 0.99. Focus is a 3px Grinder Blue outline at 3px offset (white on navy; amber inside the form).

### Chips
- **Style:** Paper pill, 2px Joint Line border, 46px tall, 16px side padding, 700 weight. The native radio/checkbox is visually hidden.
- **State:** selected fills Outline Ink with Paper text. Same look for single-choice (radio) and multi-choice (checkbox) groups.

### Cards / Containers
- **Facebook link card (navy only):** 14px corners, 2.5px white border, 6% white wash rising to 14% on hover, 52px white icon disc, trailing arrow pushed right. Sits under the before/after sliders and reads "See more of our work on Facebook".
- **Confirmation panel:** Paper, 2px Joint Line border, 14px corners, 18px padding; shows the composed message in body-sized pre text.

### Inputs / Fields
- **Style:** Paper fill, 2px Joint Line border, 12px corners, 54px minimum (textarea 110px, vertical resize), 13px/15px padding, 500 weight at body size. Labels sit above at Label weight; "(optional)" in Soft Ink at 500.
- **Focus:** border turns Outline Ink and a 3px Warning-Light Amber outline appears at 2px offset.
- **Error:** border and message in Error Red; message is plain, specific, and says why the field matters.

### Navigation
There is no navigation. The header is the logo (138-200px wide) and the tap-to-call number (800 weight, tabular numerals, Grinder Blue phone icon; 1.25rem from 1024px). The footer holds only the company name and a Facebook link.

### Service Rows
A ruled list, not cards. Each row is a full-width link (66px minimum) with the uppercase service name left and a 44px circular arrow right, separated by 1.5px Joint Line rules top and bottom. On hover or focus, only the arrow reacts: it fills Grinder Blue with a white arrow, and keyboard focus draws the outline around the arrow, not the row. On phones a row opens a pre-written text; on hover-capable desktops it jumps to the form with that service ticked.

### Before/After Slider (signature)
Real jobs, compared by hand, in the navy work band under the heading "Before and after" and a one-line "Drag the line." note. Each frame is 4:3 with a 2.5px white border and 14px corners; the after photo fills it and the before photo is clipped from the left to the divider position. Uppercase Tag pills read "Before" (top-left) and "After" (top-right) on a 72% Outline Ink wash. The divider is a 3px white line with a 44px white round knob carrying a navy double-arrow; the knob is a keyboard slider (arrows step 5%, Home/End to the ends) with an amber focus ring. Mouse and pen drag immediately; touch only takes over once the drag is clearly sideways (8px, more horizontal than vertical), so vertical scrolling still works. The first time a slider is 60% in view and untouched, it sweeps once either side of centre over 1.8s and settles at 50%; no sweep under reduced motion.

### Saw-Cut Joint
The divider between two floor sections: a 3px strip, 2px dark groove over a 1px highlight, full-bleed. It is part of the floor, not a rule drawn on it.

### Epoxy-Pour Edge (signature)
An inline SVG (viewBox 1440x80, stretched) only where the floor meets a navy band. Its background is transparent so the floor shows through; the path is navy, with the pour shadow beneath. Where navy sits above the floor the edge is flipped vertically (`scaleY(-1)`). Height 46px, 64px from 600px, 84px from 1024px. The edge is three summed sines that roll slowly (`SPEED 0.0006`, `AMP 7` viewBox units) with a per-edge phase offset; a nearby pointer pushes the edge away by up to `PUSH 16` units on a springy, damped bump. Only animates while on-screen.

### Motion and Reduced Motion
One shared requestAnimationFrame loop runs only while a visible job needs it (pour edges, slider sweeps). UI transitions are 0.15-0.2s colour changes; smooth anchor scrolling. Reflections are not on the loop: they are set directly in the scroll event, translateY = row position minus scrollY x `RATE 0.45`, with no easing and no stretch; rows (`GAP 0.6` screen heights, min 240px) are re-dressed only while off screen. Under `prefers-reduced-motion: reduce`: all CSS transitions are removed, scroll is instant, reflections move 1:1 with the floor, pour edges render once and stay still, and sliders skip their sweep.

## Do's and Don'ts

### Do:
- **Do** set dark bands in opaque Tagline Navy with its masked radial glow, and text on them in On-Navy / On-Navy Soft.
- **Do** join floor to floor with a saw-cut joint, and floor to navy with an epoxy-pour edge (flipped when navy is above).
- **Do** let light sections sit directly on the tiled floor, with no background colour of their own.
- **Do** keep the first-screen header to the logo and the tap-to-call number (top right), and let it scroll away.
- **Do** use outlined pills (2.5px Outline Ink, 58px) for actions, with Grinder Blue fill for the primary.
- **Do** set blue type on the concrete in Pressed Blue.
- **Do** give every form control (inputs, textarea, chips, the submit button) a 3px Warning-Light Amber outline on hover and focus, paired with the Outline Ink border shift on text fields so focus never depends on amber alone.
- **Do** let only the arrow react when a service row is hovered or focused.
- **Do** keep touch targets at or above 44px and use tabular numerals for the phone number.
- **Do** honour reduced motion exactly as above: reflections locked to the floor, still pours, no slider sweep, no transitions.

### Don't:
- **Don't** load a webfont; the system stack is the owner's choice.
- **Don't** add a sticky header, sticky call bar, or any fixed UI; the only fixed layer is the reflections, behind content and ignoring the pointer.
- **Don't** repeat the phone number elsewhere in the first screen; it appears top right, then in the close band.
- **Don't** add an email address, mailto link, or contact channel other than phone/text and Facebook.
- **Don't** highlight, underline, outline or tint a whole service row on hover; the arrow carries the state.
- **Don't** use black or near-black grounds.
- **Don't** use amber outside hands-on controls (form controls, the slider knob).
- **Don't** separate sections with boxes, cards or decorative rules; the saw-cut joint is the only straight divider.
- **Don't** put a pour between two floor sections; pours exist only where navy meets the floor.
