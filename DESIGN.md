---
name: Guion · Sistema de Gestión Cielo Abierto
description: A private dark presenter view that keeps one speaker on text and on pace through a timed talk (10:40).
colors:
  ground: "#0d1218"
  raise: "#141b23"
  raise-2: "#1a232d"
  line: "#26313d"
  line-2: "#334150"
  selected: "#2b3846"
  ink: "#eef2f6"
  ink-2: "#c3ccd6"
  mute: "#93a1b0"
  ok: "#5cc98a"
  ok-edge: "#2c5a40"
  ok-soft: "#9fd8b7"
  warn: "#f2b84b"
  warn-wash: "#2a2110"
  cue-ink: "#f0d28f"
  cue-edge: "#6e5a2c"
  cue-wash: "#1c1810"
  over: "#f2705f"
  over-ink: "#ffb3a8"
  over-hatch-light: "#3a1510"
  over-hatch-dark: "#2a100c"
  over-hatch-deep: "#7a2a20"
  focus: "#8fb7ff"
  selection: "#2f5b8f"
  plate: "#f6f7f9"
typography:
  display:
    fontFamily: "Segoe UI Variable Display, Segoe UI, system-ui, -apple-system, Helvetica Neue, Roboto, Arial, sans-serif"
    fontSize: "clamp(42px, 4vw, 60px)"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "-0.02em"
    fontFeature: "\"tnum\" 1"
  headline:
    fontFamily: "Segoe UI Variable Display, Segoe UI, system-ui, -apple-system, Helvetica Neue, Roboto, Arial, sans-serif"
    fontSize: "clamp(30px, 2.6vw, 38px)"
    fontWeight: 650
    lineHeight: 1
    letterSpacing: "-0.01em"
    fontFeature: "\"tnum\" 1"
  title:
    fontFamily: "Segoe UI Variable Display, Segoe UI, system-ui, -apple-system, Helvetica Neue, Roboto, Arial, sans-serif"
    fontSize: "clamp(28px, 2.4vw, 36px)"
    fontWeight: 650
    lineHeight: 1.15
    letterSpacing: "-0.01em"
  reading:
    fontFamily: "Segoe UI Variable Text, Segoe UI, system-ui, -apple-system, Helvetica Neue, Roboto, Arial, sans-serif"
    fontSize: "clamp(24px, calc(1.4vw + 6px), 30px)"
    fontWeight: 400
    lineHeight: 1.42
  body:
    fontFamily: "Segoe UI Variable Text, Segoe UI, system-ui, -apple-system, Helvetica Neue, Roboto, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  control:
    fontFamily: "Segoe UI Variable Text, Segoe UI, system-ui, -apple-system, Helvetica Neue, Roboto, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 650
    lineHeight: 1.5
  label:
    fontFamily: "Segoe UI Variable Text, Segoe UI, system-ui, -apple-system, Helvetica Neue, Roboto, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.06em"
rounded:
  step: "4px"
  key: "5px"
  pill: "8px"
  control: "10px"
  panel: "12px"
  plate: "14px"
spacing:
  gutter: "clamp(20px, 3vw, 44px)"
  bar-gap: "clamp(18px, 2.4vw, 36px)"
  stage-gap: "clamp(28px, 4vw, 64px)"
  control-gap: "10px"
  step-gap: "3px"
components:
  button-play:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.ground}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    padding: "9px 14px"
    width: "118px"
  button-play-running:
    backgroundColor: "{colors.raise-2}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
  button-secondary:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.ink}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    padding: "9px 14px"
  button-secondary-hover:
    backgroundColor: "{colors.raise-2}"
  mode-switch:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.mute}"
    rounded: "{rounded.control}"
    padding: "3px"
  mode-switch-active:
    backgroundColor: "{colors.selected}"
    textColor: "{colors.ink}"
    rounded: "7px"
    padding: "7px 12px"
  part-clock:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.ink}"
    typography: "{typography.headline}"
    rounded: "{rounded.panel}"
    padding: "7px 14px 8px"
  part-clock-ok:
    textColor: "{colors.ok}"
  part-clock-warn:
    backgroundColor: "{colors.warn-wash}"
    textColor: "{colors.warn}"
  part-clock-over:
    backgroundColor: "{colors.over-hatch-light}"
    textColor: "{colors.over-ink}"
  progress-step:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.step}"
    padding: "6px 10px 8px"
  progress-step-current:
    backgroundColor: "{colors.selected}"
    textColor: "{colors.ink}"
  cue-pill:
    backgroundColor: "{colors.cue-wash}"
    textColor: "{colors.cue-ink}"
    rounded: "{rounded.pill}"
    padding: "6px 12px 6px 10px"
  next-note:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.mute}"
    rounded: "{rounded.panel}"
    padding: "16px 18px"
  diagram-plate:
    backgroundColor: "{colors.plate}"
    rounded: "{rounded.plate}"
    padding: "clamp(14px, 2vw, 24px)"
---

# Design System: Guion · Sistema de Gestión Cielo Abierto

## Overview

**Creative North Star: "The Presenter's Instrument Panel"**

A category-standard dark presenter view held to Keynote and PowerPoint presenter craft. The screen belongs to two things: the clock and the words about to be spoken. Everything else (mode switch, progress line, the "Sigue:" note, key hints) sits one or two steps down in tone on a blue-black ground so it recedes until it is needed. The page is read at arm's length in a lit classroom, so contrast is high, type is large, and every state change is carried by colour, pattern and words together.

Density is low where the speaker reads and compact where he glances: a single sticky top band holds both clocks, the part title, the pace line and the controls, with a thin segmented progress line under it; below, one reading column of about 820px with a narrow note at its right. Colour is functional, never decorative. Green means on pace, amber means the last 15 seconds of a part, red with a diagonal hatch means over time. Diagrams are the one light surface: they arrive on pale plates exactly as their light exports were drawn.

The tone is sober, as the subject requires. No imagery beyond the speech's own diagrams, no brand marks, no ornament.

**Key Characteristics:**
- Blue-black tonal layering (ground, raise, raise-2) instead of shadows for chrome.
- Two clocks with tabular numerals; the total clock is the largest numeral on screen.
- A three-state timing vocabulary (on pace, last 15 s, over) carried by colour, hatch and label at once.
- Projector cues as small amber-outlined pills, visually separate from spoken prose.
- Light diagram plates as the only bright surface.
- One authored motion: the diagram plate rises in after a part change.

## Colors

A cool blue-black instrument palette with three signal hues reserved for time and cues, plus one pale plate for diagrams.

### Primary
- **Reading White** (ink): the spoken text, current-part titles, clock numerals at rest, and the filled play button. The page's primary voice is the words, so the "primary" colour is the reading ink itself.

### Secondary
- **Pace Green** (ok): the part clock and its progress segment while the part is on pace. Its edge companion **Pace Green Edge** (ok-edge) outlines the on-pace part clock. **Soft Pace Green** (ok-soft) is the quiet text form for "adelantado" in the pace line and for under-plan differences in the practice table.
- **Last-Seconds Amber** (warn): the part clock and its segment in the final 15 seconds of a part, over **Amber Wash** (warn-wash); also the icon colour inside cues and the authorization note.

### Tertiary
- **Over-Time Red** (over): the border of an over-time clock and the light stripe of over-time hatches. **Over Text** (over-ink) is the readable red-pink used for "Excedido +m:ss", "atrasado" and over-plan differences. **Hatch Light / Hatch Dark** (over-hatch-light, over-hatch-dark) form the 135° stripe behind over-time clocks; **Hatch Deep** (over-hatch-deep) is the dark stripe in thin over-time bars and segments.
- **Cue Amber** family: **Cue Ink** (cue-ink) text, **Cue Edge** (cue-edge) outline and **Cue Wash** (cue-wash) fill for projector cues, the "Pantalla:" line in the note, and the authorization-letter note.

### Neutral
- **Night Ground** (ground): page, sticky top band, scrollbar track.
- **Raised Slate** (raise): controls, part clock, progress steps, the "Sigue:" note, closed Q&A items, the current row in the practice table.
- **Raised Slate 2** (raise-2): hover fill, open Q&A items, running play button, meter tracks, keycaps.
- **Hairline** (line) and **Strong Hairline** (line-2): 1px dividers and control borders; line-2 also fills idle progress bars and the scrollbar thumb.
- **Selected Slate** (selected): the pressed mode-switch segment and the current progress step.
- **Secondary Ink** (ink-2): answers, the next part's first words, labels inside chrome, the planned-time mark in meters.
- **Muted Ink** (mute): clock labels, meta lines, captions, hints, key legend.
- **Focus Blue** (focus): the 2px focus-visible outline. **Selection Blue** (selection): text selection.
- **Diagram Plate** (plate): the light ground under every diagram.

### Named Rules
**The Signal-Only Hue Rule.** Green, amber and red appear only to report time (or, for the cue amber family, to mark what goes on the projector). No hue is used for decoration, branding or emphasis of spoken words.

**The Never-Colour-Alone Rule.** Over time is always red plus a 135° diagonal hatch plus a "+m:ss" or "Excedido" label. Last seconds are amber plus the "Quedan" label. Any new timing state must carry pattern or words, not colour only.

**The Green-Means-On-Pace Rule.** Pace Green is reserved for on-pace and under-plan readings. Idle, paused and neutral states use Muted Ink, never green.

## Typography

**Display Font:** Segoe UI Variable Display (with Segoe UI, system-ui, -apple-system, Helvetica Neue, Roboto, Arial)
**Body Font:** Segoe UI Variable Text (with the same fallback stack)

**Character:** The operating system's own UI sans, as presenter views use: local, offline, and familiar at a glance. Hierarchy comes from size and weight (400 to 700, with 650 as the house semibold), never from a second family.

### Hierarchy
- **Display** (700, clamp(42px, 4vw, 60px), 1): the total clock only. It is the largest numeral on the page.
- **Headline** (650, clamp(30px, 2.6vw, 38px), 1): the part clock. Plan suffixes ("/ 10:40" (computed from the speech), "/ 1:20") drop to 500 at clamp(17px, 1.5vw, 22px) in Muted Ink.
- **Title** (650, clamp(28px, 2.4vw, 36px), 1.15): view titles; section heads in the full script at 26px; the bar's part title at clamp(17px, 1.35vw, 20px).
- **Reading** (400, clamp(24px, calc(1.4vw + 6px), 30px), 1.42, paragraph gap .55em, max 34em): the spoken words in Presentar. The speaker can step it with + / − in 2px increments, clamped to 20–36px. The full script reads at 22px; Q&A answers at clamp(21px, 1.6vw, 24px).
- **Body** (400, 15–16px, 1.5): meta lines, the "Sigue:" note, captions, practice table (17px).
- **Control** (600–650, 14px): buttons, mode switch, the "Sigue abajo" cue.
- **Label** (600–700, 12–12.5px, 0.06em, uppercase): clock labels ("Total", "Esta parte") and practice table headers only.

### Named Rules
**The Tabular Clock Rule.** Every time value (clocks, step times, plan and measured columns, history) uses tabular numerals so digits never jitter while counting.

**The Spoken-Text Floor Rule.** Spoken words never render below 20px, in any view or at any reading-size setting.

## Layout

A sticky top band and a centred reading stage. The band is a single flex row with gaps of clamp(18px, 2.4vw, 36px) and side gutters of clamp(20px, 3vw, 44px): total clock, part clock, part title with pace line (flexible), then the mode switch and play/fullscreen controls. Directly under it, the progress line runs full width with 3px gaps; each step's width is proportional to its planned duration (the Jurado step takes a fixed share), and a 3px fill bar along its bottom edge reports progress in the state colour.

The Presentar stage is a two-column grid: reading column up to 820px plus a 200–270px "Sigue:" note, centred with a gap of clamp(28px, 4vw, 64px). The note is sticky under the top band. The part's diagram sits under the text; a wide diagram (aspect above 1.8) spans both columns. Below 1180px the note drops under the reading column (static, max 820px) and mode-switch segments tighten.

The full script (max 860px) and practice view (max 980px) are single centred columns separated by hairline section rules. When the current part's text runs past the viewport, a fixed "Sigue abajo ↓" cue fades in at the bottom over a gradient into the ground. Scroll padding equals the top band's height so anchored content is never hidden under it.

## Elevation & Depth

Chrome is flat and layered by tone: ground, raise, raise-2 and selected step up in lightness to show nesting and state. Shadows appear only where something floats above the reading plane.

### Shadow Vocabulary
- **Plate lift** (`box-shadow: 0 2px 6px rgba(0,0,0,.35), 0 14px 40px rgba(0,0,0,.35)`): the light diagram plate, so it sits above the dark ground.
- **Toast lift** (`box-shadow: 0 6px 24px rgba(0,0,0,.5)`): the transient status toast.
- **Pressed segment** (`box-shadow: 0 1px 2px rgba(0,0,0,.4)`): the active mode-switch segment.
- **Current-step ring** (`box-shadow: inset 0 0 0 1px` Secondary Ink): the current progress step.

### Named Rules
**The Tonal-Chrome Rule.** Controls, clocks, notes and list items are separated by tone and 1px hairlines, never by drop shadows.

## Shapes

Softly rounded rectangles throughout, with radius growing with the size of the surface: 4px progress steps, 5px keycaps, 7px mode-switch segments, 8px cue pills, 10px buttons and the segmented control, 12px clocks, notes and Q&A panels, 14px diagram plates. Borders are 1px hairlines; keycaps add a 2px bottom edge. The only non-rectangular motif is the 135° stripe that marks over time (8px stripes behind clocks, 5px in thin bars and segments).

## Components

### Buttons
- **Shape:** gently rounded (10px), 1px Strong Hairline border, 9px 14px padding, Control type, icon and label 8px apart.
- **Primary (play):** filled Reading White with Night Ground text, min width 118px; hover goes to pure white. While running it inverts to Raised Slate 2 with ink text and reads "Pausar".
- **Secondary:** Raised Slate fill; hover to Raised Slate 2. Icon-only variant uses 9px padding (fullscreen).
- **Focus:** 2px Focus Blue outline, 3px offset.

### Mode switch
- **Style:** a segmented control on Raised Slate with a 1px hairline and 3px inner padding; segments are text buttons in Muted Ink ("Presentar", "Guion completo", "Práctica").
- **State:** the pressed segment fills Selected Slate with white text and the pressed-segment shadow; hover lifts text to ink.

### Clocks (signature component)
- **Total clock:** label "Total", Display numerals, plan suffix computed from the speech ("/ 10:40"). Transparent at rest; when over time it gains an Over-Time Red border, the 8px hatch and "Excedido +m:ss" in Over Text.
- **Part clock:** label "Esta parte", Headline numerals, plan suffix, a state line. Raised Slate panel with hairline. On pace: Pace Green Edge border, green numerals, "Quedan m:ss". Last 15 s: amber border on Amber Wash, amber numerals. Over: red border, hatch, Over Text, "Excedido +m:ss". Idle: muted "Sin empezar". Background and border transition over 0.3s on the expo-out ease.

### Progress line
- **Style:** full-width row of Raised Slate steps (4px radius) showing number, short name (ellipsised) and time; step width follows planned duration.
- **State:** current step fills Selected Slate with an inset Secondary Ink ring and white text. The bottom 3px fill bar is Strong Hairline when idle, then green, amber, or the red 5px hatch; over-time steps show "+m:ss" in bold Over Text. Steps are buttons that jump to their part.

### Cue pill
- **Style:** inline-flex pill, 8px radius, Cue Edge outline on Cue Wash, Cue Ink text at 15px/600, a 17px screen icon in Last-Seconds Amber. Sits between paragraphs, never inside one.

### "Sigue:" note
- **Style:** Raised Slate panel, 12px radius, 16px 18px padding, sticky beside the reading column. Holds "Sigue:" plus the next part's number and title (18px/650 ink), its start and duration, a "Pantalla:" cue line in Cue Ink, the next part's first twelve words in quotes (Secondary Ink, 15.5px), and a hairline-separated key hint.

### Q&A panels
- **Style:** disclosure panels on Raised Slate with hairline and 12px radius; open state moves to Raised Slate 2 with Strong Hairline, and the chevron rotates 90° over 0.25s. Questions at clamp(20px, 1.6vw, 23px)/650; answers in Secondary Ink. The authorization note below uses the cue amber family with an alert icon.

### Practice table and meter
- **Style:** full-width table, uppercase Label headers over a Strong Hairline, 1px row rules, right-aligned tabular numbers, current row on Raised Slate. Over-plan differences in bold Over Text, under-plan in Soft Pace Green.
- **Meter:** 10px Raised Slate 2 track, green fill (red 5px hatch when over), and a 2px Secondary Ink mark at the planned time.

### Diagram plate
- **Style:** Diagram Plate ground, 14px radius, clamp(14px, 2vw, 24px) padding, Plate lift shadow, Muted Ink caption below. On part change it rises in (opacity 0 and 12px down to rest, 0.5s on cubic-bezier(.16,1,.3,1), 0.12s delay); no motion under prefers-reduced-motion.

### Overflow cue and toast
- **"Sigue abajo":** fixed 84px band at the bottom, gradient from transparent into Night Ground, Control-weight Secondary Ink text with a ↓ keycap; fades in over 0.2s only while text remains below.
- **Toast:** Reading White fill with Night Ground text, 10px radius, Toast lift, bottom right; slides 16px and fades.

## Do's and Don'ts

### Do:
- **Do** keep the total clock the largest numeral on screen (clamp(42px, 4vw, 60px), 700) and the part clock next (clamp(30px, 2.6vw, 38px)).
- **Do** pair every over-time reading with the 135° hatch and a "+m:ss" or "Excedido" label.
- **Do** use tabular numerals for every time value.
- **Do** keep spoken text at 20px or more, and the Presentar reading size between 24px and 30px by default.
- **Do** render projector cues as amber-outlined pills, separate from spoken paragraphs.
- **Do** place diagrams on the light plate with the plate lift shadow.
- **Do** separate chrome by tone (ground, raise, raise-2, selected) and 1px hairlines.
- **Do** stop all motion under prefers-reduced-motion.

### Don't:
- **Don't** use green for idle, paused or neutral states; it means on pace.
- **Don't** signal over time by colour alone.
- **Don't** add drop shadows to controls, clocks, notes or panels.
- **Don't** add slide thumbnails or widen the "Sigue:" note beyond a narrow note.
- **Don't** introduce a second type family or web fonts; the page must work offline from disk.
- **Don't** add photos, logos or institutional branding.
