---
name: Hartielectrocool Climatización
description: A one-page climate-service site seen through a thermal camera; heat is the subject and cold is the fix.
colors:
  ground: "#0b0716"
  ground-raised: "#140c26"
  ink-violet: "#120a24"
  line: "rgba(244, 236, 255, 0.14)"
  bone: "#f6f1ea"
  lilac-soft: "#c9bfd9"
  logo-orange: "#f7931e"
  ember-red: "#e8462a"
  white-hot: "#ffe9a8"
  sodium-yellow: "#ffd23f"
  logo-cyan: "#2bb3e8"
  logo-blue: "#1673c9"
  deep-cold: "#0a1a5c"
  iron-violet: "#5b1a8a"
  iron-magenta: "#b5176b"
  ink-on-hot: "#1b0c02"
typography:
  display:
    fontFamily: "Unbounded, Arial Black, system-ui, sans-serif"
    fontSize: "clamp(2.6rem, 6.4vw, 5.6rem)"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Unbounded, Arial Black, system-ui, sans-serif"
    fontSize: "clamp(2.2rem, 5.4vw, 4.6rem)"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Unbounded, Arial Black, system-ui, sans-serif"
    fontSize: "clamp(1.5rem, 2.8vw, 2.3rem)"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  title-sm:
    fontFamily: "Unbounded, Arial Black, system-ui, sans-serif"
    fontSize: "1.2rem"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Manrope, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  lead:
    fontFamily: "Manrope, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(17px, 1.3vw, 19px)"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Manrope, Segoe UI, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: "0.01em"
  readout:
    fontFamily: "JetBrains Mono, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "13px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.04em"
    fontFeature: "tnum"
  hud:
    fontFamily: "JetBrains Mono, ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.3
    letterSpacing: "0.08em"
rounded:
  meter: "6px"
  tag: "8px"
  field: "12px"
  tile: "14px"
  card: "20px"
  panel: "22px"
  pill: "999px"
spacing:
  gutter: "clamp(16px, 4vw, 56px)"
  container: "1320px"
  section: "clamp(90px, 12vw, 170px)"
  head-gap: "clamp(44px, 6vw, 80px)"
  frame-pad: "clamp(22px, 3vw, 36px)"
  chip-gap: "10px"
  action-gap: "12px"
components:
  button-hot:
    backgroundColor: "{colors.logo-orange}"
    textColor: "{colors.ink-on-hot}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "54px"
  button-line:
    backgroundColor: "rgba(11, 7, 22, 0.35)"
    textColor: "{colors.bone}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "54px"
  button-line-hover:
    backgroundColor: "rgba(43, 179, 232, 0.12)"
    textColor: "#ffffff"
  chip:
    backgroundColor: "transparent"
    textColor: "{colors.bone}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.bone}"
    textColor: "{colors.ink-violet}"
    rounded: "{rounded.pill}"
  input:
    backgroundColor: "rgba(255, 255, 255, 0.04)"
    textColor: "{colors.bone}"
    rounded: "{rounded.field}"
    padding: "14px 16px"
    height: "52px"
  input-focus:
    backgroundColor: "rgba(43, 179, 232, 0.06)"
  system-card:
    backgroundColor: "{colors.ground-raised}"
    textColor: "{colors.bone}"
    rounded: "{rounded.card}"
    padding: "20px 18px 22px"
  message-ticket:
    backgroundColor: "#0f0a1e"
    textColor: "#eae3f4"
    rounded: "{rounded.panel}"
    padding: "22px 20px"
  brand-tile:
    backgroundColor: "#ffffff"
    rounded: "{rounded.tile}"
    padding: "14px 18px"
    height: "84px"
  nav-link:
    textColor: "{colors.lilac-soft}"
    typography: "{typography.label}"
---

# Design System: Hartielectrocool Climatización

## Overview

**Creative North Star: "The Thermal Viewfinder"**

Everything is seen through a thermal camera. The ground is a cold violet-black, the image space where nothing is warm yet. Heat shows up as the iron ramp (violet, magenta, ember red, the logo's orange, sodium yellow, white-hot), and cold shows up as the logo's own cyan and blue. The two halves of the brand mark become the two ends of one temperature scale, so the palette is a measuring instrument and not decoration.

The camera's HUD supplies the structural vocabulary: corner brackets that frame a region, a crosshair spot meter, min/max readouts, and a vertical scale bar. Readings are set in a monospaced face because they are measurements. Around them, headlines are heavy and wide (Unbounded 800, tight tracking), and running text is plain, friendly Manrope. Outside the two live thermal fields (hero and closing band), sections are calm and dark. They open with a single camera scan line, the only reveal motion in the system.

The page is dense where it has to act, with the quote form and live message ticket side by side, and generous between sections (90 to 170px of vertical rhythm). It refuses the category default: no stock photo of a smiling technician beside a split unit, and no row of three service cards.

**Key Characteristics:**
- Cold violet-black ground; heat and cold are the only saturated colors.
- One temperature ramp (`deep-cold` to white-hot) reused as scale bar, slider track, scan line, ticket rule and hover wash.
- HUD devices: corner brackets, spot meter crosshair, mono readouts, scale bar.
- Heavy wide display type over a quiet humanist body.
- Pill-shaped actions; softly rounded containers; white tiles reserved for partner logos.
- One motion grammar: the scan-line reveal.

## Colors

A night-vision palette: near-black violet neutrals, with the full thermal iron ramp for heat and the logo's cyan and blue for cold.

### Primary
- **Logo Orange** (`logo-orange`): the hot accent and the only filled call to action ("Pedir presupuesto"), the "hoy" marker in the hours table, text selection, the caret and the scrollbar. It is the logo's own warm half.
- **Logo Cyan** (`logo-cyan`): the cold accent. Cold words in the hero headline, input focus rings, contact icons, card links ("Pedir precio") and the outline-button hover. It is the logo's own cool half.

### Secondary
- **Ember Red** (`ember-red`): the hot end below orange. Used for the recording dot, the "closed" status and the hot service-row wash.
- **Logo Blue** (`logo-blue`): the cold end below cyan; it appears in the ramp, the system thumbnails and the cold service-row wash.

### Tertiary (ramp stops)
- **Deep Cold** (`deep-cold`): the coldest stop. It is also the background of the closing band behind its live field.
- **Iron Violet** (`iron-violet`) and **Iron Magenta** (`iron-magenta`): middle temperatures. They appear only inside the ramp, the thermal thumbnails and the hot hover wash, never as flat UI fills.
- **Sodium Yellow** (`sodium-yellow`): near the top of the ramp.
- **White-Hot** (`white-hot`): the hottest reading color. Used for HUD values, mono readouts and the global focus outline.

### Neutral
- **Ground** (`ground`): the page background and the theme color.
- **Ground Raised** (`ground-raised`): the brand band and system cards.
- **Ink Violet** (`ink-violet`): the hero base, and dark text on bone-filled states (selected chip, hovered link pill, hovered social icon).
- **Bone** (`bone`): primary text, warm off-white.
- **Lilac Soft** (`lilac-soft`): secondary text, nav links, hints, table values.
- **Line** (`line`): every 1px hairline (section borders, list dividers, inset card strokes).
- **Ink on Hot** (`ink-on-hot`): text on orange fills.

### Named Rules
**The Two-Ended Scale Rule.** Saturated color means temperature. Warm hues (violet through white-hot) mark heat, problems and the main action; cyan and blue mark cooling, focus and the fix. No saturated hue is used for anything that is not on the scale.

**The One Ramp Rule.** The thermal gradient has one definition (`deep-cold`, `logo-blue` 18%, `logo-cyan` 32%, `iron-violet` 48%, `iron-magenta` 62%, `ember-red` 74%, `logo-orange` 86%, `sodium-yellow` 94%, `#fff3cf`). Every scale bar, slider, scan line, ticket rule and canvas palette uses these stops in this order.

## Typography

**Display Font:** Unbounded (with Arial Black, system-ui)
**Body Font:** Manrope (with Segoe UI, system-ui)
**Label/Mono Font:** JetBrains Mono (with ui-monospace, SFMono-Regular, Menlo)

**Character:** Unbounded at 800 is wide and heavy, close to the logo's rounded wordmark, and carries every heading. Manrope keeps the body plain and easy to read. JetBrains Mono with tabular figures is the camera's voice and is reserved for readings.

### Hierarchy
- **Display** (800, clamp 2.6–5.6rem, 1.02, -0.03em): the hero headline only, max 12ch, balanced wrap.
- **Headline** (800, clamp 2.2–4.6rem, 1.02): section titles; the closing band goes up to 5.6rem at 14ch.
- **Title** (800, clamp 1.5–2.3rem): service rows. **Title small** (1.2rem, -0.02em): system cards.
- **Body** (400, 17px, 1.6): running text; secondary paragraphs in `lilac-soft` at 46–48ch.
- **Lead** (400, 17–19px): the one sentence under a headline, max 48ch.
- **Label** (700, 15px, 1.4): buttons (15px, 14px in the nav), form legends and field labels.
- **Readout** (600, 13px, 0.04em, tabular): measured values in `white-hot`; the large slider value goes up to 2.2rem.
- **HUD** (500, 12px, 0.08em, uppercase): camera overlay text on the live fields and scale ticks.

### Named Rules
**The Measurement Rule.** Monospace is for readings only: temperatures, kW and frigoría values, m², times and live status. Running text and headings never use it.

## Layout

Single column of full-bleed sections inside a centered container (max 1320px, side gutter clamp 16–56px). Sections breathe at clamp 90–170px vertically. Section heads are a two-column grid (1.2fr / 1fr, headline left, supporting copy right, aligned to the bottom) with stacked, split and contact variants. Head-to-content gap is clamp 44–80px.

The hero fills the viewport (100svh) with the live field. Copy sits left, the scale bar sits on the right edge, and a left-to-right vignette keeps the copy readable. The quote section is a 1.25fr / 1fr grid: the form on the left, a sticky message ticket on the right (top 100px).

At 980px and below, every grid collapses to one column. Nav links move into a dropdown, the system cards become a horizontal snap scroller (72% card width, bleeding to the gutter), the ticket stops being sticky, and a fixed bottom action bar (quote and call) slides up. At 760px and below, the hero scale bar turns horizontal along the bottom. At 640px and below, the brand tiles go two-up, form rows stack and hero buttons go full width.

## Elevation & Depth

Depth is mostly tonal: `ground` to `ground-raised` to translucent white washes (0.03–0.08), with 1px inset hairlines in `line` instead of borders. Shadows are soft and dark, used for lift under actionable or floating objects, never as outlines. Glow is used once, as a status halo.

### Shadow Vocabulary
- **Action lift** (`0 10px 24px -14px rgba(0,0,0,.7)`, hover `0 16px 30px -14px rgba(0,0,0,.8)`): the hot button.
- **Panel drop** (`inset 0 0 0 1px line, 0 30px 70px -40px rgba(0,0,0,.85)`): the message ticket.
- **Badge lift** (`0 0 0 3px rgba(255,255,255,.08), 0 8px 20px -10px rgba(0,0,0,.7)`): the white logo disc.
- **Thumb** (`0 0 0 5px rgba(11,7,22,.85), 0 6px 18px rgba(0,0,0,.4)`): the range slider thumb.
- **Status halo** (`0 0 0 4px rgba(52,210,123,.18)`): the "open now" dot.

### Named Rules
**The Hairline Rule.** Containers are separated by 1px `line` insets or rules, not by shadows. A shadow means "this floats or can be pressed".

## Shapes

Two families. Actions are pills (999px): buttons, chips, service links, status, social circles. Containers are softly rounded and get larger with their size: 6px meter label, 8px thumbnail tags, 12px fields, 14px brand tiles and contact rows, 20px system cards, 22px ticket. The HUD adds square corner brackets (24–26px arms, 2px stroke) that frame the hero, the closing band and every section head. Brackets are drawn, never boxed. The logo sits on a white disc.

## Components

### Buttons
- **Shape:** full pill (999px), 54px tall (46px in nav, 50px in mobile bar), 26px side padding, 12px icon gap.
- **Hot (primary):** `logo-orange` fill, `ink-on-hot` text. On hover it lifts 2px and the full ramp fades in across the fill; the trailing arrow nudges 3px. One per view region.
- **Line (secondary):** bone 1.5px inset ring on a translucent ground. On hover the ring turns cyan and the fill gets a faint cyan wash: the cold counterpart to the hot button.
- **Active:** scale 0.97. **Pending** (contact data not yet supplied): transparent with a lilac ring and default cursor.
- **Focus:** 2px `white-hot` outline, 3px offset (global).

### Chips
- **Style:** 46px pill, 1.5px bone inset ring at 25%, Manrope 600 15px.
- **State:** hover strengthens the ring to 60%; selected fills with `bone` and `ink-violet` text; focus is the white-hot outline on the visible pill. They are radio inputs.

### Cards / Containers
- **System card:** 20px radius, `ground-raised`, 1px `line` inset, a 4:5 blurred thermal thumbnail with a white line drawing of the unit, a body tag and a mono spot reading, then title, copy and a cyan link.
- **Message ticket:** 22px radius on `#0f0a1e` with the panel drop, a header with a green WhatsApp dot, a 4px ramp rule, and the prefilled message in mono.
- **Brand tile:** white 14px tile, min 84px tall, where partner logos sit at their real colors.

### Inputs / Fields
- **Style:** 12px radius, 4% white fill, 1.5px bone inset ring at 18%, 52px min height, Manrope 500 16px.
- **Focus:** the ring becomes 2px `logo-cyan` with a faint cyan wash (focusing is cooling).
- **Range:** a 10px ramp track with a 26px white thumb; the value reads above in large mono, with an orienting frigoría/kW readout below.

### Navigation
- Fixed and transparent over the hero; it turns 92% ground with a hairline once scrolled. The logo badge sits left (white disc and Unbounded name), links in `lilac-soft` Manrope 600 15px turn bone on hover, and a compact hot button sits on the right. At 980px and below, a round menu button opens a full-width list with 18px links and hairline dividers.

### Service Rows (signature)
- A ruled list rather than cards: title, copy, and a pill "Presupuesto" link per row. On hover a temperature wash sweeps in from the left (cold rows get `deep-cold` to cyan, hot rows get violet to ember to orange).

### Thermal Field and Spot Meter (signature)
- A canvas field of drifting warm sources, mapped through the One Ramp. The pointer (or an automatic sweep on touch) acts as a cold source, while a crosshair spot meter reads °C in mono. Corner brackets, a REC-style HUD and a scale bar with live max/min frame it. The field pauses off-screen and under reduced motion.

### Scan-Line Reveal (motion)
- Each section's content unclips top-to-bottom over 1.1s (`cubic-bezier(.16, 1, .3, 1)`) as a 3px ramp line travels down it. It triggers once at 12% visibility, and reduced motion removes it.

## Do's and Don'ts

### Do:
- **Do** keep saturated color on the temperature scale: warm for heat and the main action, `logo-cyan`/`logo-blue` for cooling and focus.
- **Do** build every gradient from the One Ramp stops, in order.
- **Do** set temperatures, power, area, times and live status in JetBrains Mono with tabular figures.
- **Do** frame important regions with HUD corner brackets (2px, 24–26px arms) rather than boxed borders.
- **Do** use pills for every action and the 6–22px rounded scale for containers.
- **Do** reveal new sections with the scan line only, and honor reduced motion.

### Don't:
- **Don't** add a second reveal or entrance animation (fades, slides, staggered pops); the scan line is the only motion grammar.
- **Don't** use stock photos of technicians or equipment; equipment is shown as thermal renderings with line drawings.
- **Don't** use iron violet or magenta as flat UI fills; they exist only inside thermal imagery and washes.
- **Don't** put partner logos directly on the dark ground; they sit on white tiles at their own colors.
- **Don't** invent figures (reviews, years, installation counts, prices); readouts show real or calculated values only.
