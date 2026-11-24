---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

# Surface brief: index.html (presenter page)

Scope: the single page `index.html`, mode Read (a private prompter read at a glance while speaking). Audience, constraints and the fixed-text rule live in PRODUCT.md.

Job: keep Jordy on pace and on text during an 8:00 talk; rehearse beforehand.
Content: the six timed parts of speech.md, four archify diagrams (light SVG, inline), the jury Q&A and the authorization-letter note.
Craft bar: Keynote presenter display and PowerPoint presenter view (the user gave no preference; these two are the stated bar).

## Direction contract

THESIS: The category-standard presenter view, executed at Keynote-presenter craft: the clock and the current part's spoken words own the screen. It refuses slide thumbnails, a "next slide" pane wider than a note, and any chrome that competes with the sentence he is about to say.

OWN-WORLD: Dark blue-black ground, off-white reading text, one calm green for "on pace", amber for the last 15 s of a part, red for over time, always paired with a hatched segment and a "+m:ss" label. System UI sans (Segoe UI Variable on Windows) with tabular numerals for every clock. Projector cues are small amber-outlined pills, never prose. Diagrams sit on light plates, as the archify light exports are.

STORY: He glances, sees where he is and how long is left, reads the next sentence, sees what to show on the projector, presses → between parts, and ends on the jury questions. In rehearsal he sees per-part measured times against the plan.

FIRST VIEWPORT: Top bar: total clock "m:ss / 8:00" (largest numerals), part clock "m:ss / plan", part title, mode switch (Presentar · Guion completo · Práctica) and play/pause at right. Under it, the full-width 7-step progress line (6 parts + Jurado), clickable. Body: reading column (~820px, 26px text; ≥24px at 1366) with cues inline; a narrow "Sigue" note at right; the part's diagram under the text.

FORM: canon (the standing exit, chosen by the user in round 3, safer register; craft bar Keynote / PowerPoint presenter). seed:9509bfc56b564fbe

SIGNATURE / MOTION: The part clock's state change (on pace → last 15 s → over, by colour, pattern and label). One authored motion: the diagram rises in (opacity + 12px, ~450 ms expo-out) after the part changes; none under prefers-reduced-motion.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance
