# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS/JS in a single `index.html`, no build step, no network dependency. Opens by double-click from disk (`file://`) and works offline. Diagrams are archify SVG exports embedded inline. Fonts use local fallbacks. (Decided by the user in the brief.)

## Users

One person: Jordy Huansi, presenting alone the Práctica Profesionalizante I folder "Sistema de Gestión Cielo Abierto" (division 31N, team of six) to a jury of professors, in a classroom. The page is a private prompter on his own laptop (1366×768 or 1440×900). It is never projected; the slides go to the projector separately. He reads it at a glance while speaking, standing near the laptop, under time pressure. He also rehearses with it beforehand.

## Product Purpose

Turn the speech (10:40 since the scope and requirements were detailed; originally 8:00) (`C:\Users\usuario\Downloads\speech.md`) into a presenter tool: show one part at a time in large text, keep the pace against the planned times, cue what to show on the projector, and keep the likely jury questions at hand. Success: he finishes within the planned total (10:40), never loses his place, and never needs to scroll or hunt mid-sentence.

## Positioning

A prompter built around this one speech and its six timed parts, not a generic slide-notes view: per-part timing taken from the speech itself, the projector cues kept visually separate from what is spoken, and the speech's own diagrams placed under the text that introduces them.

## Operating Context

- Six parts with fixed starts and durations: 1:20, 1:20, 1:30, 2:30, 2:50, 1:10 (total 10:40; parts 4 and 5 were extended to detail requirements, limits and scope), then "Preguntas probables del jurado".
- Lines in [brackets] are projector cues, not spoken. Lines {Diagrama: …} mark where each diagram goes.
- Keyboard only (no clicker): Space start/pause, ← → change part, F fullscreen, R reset.
- Two uses: live presentation (presenter mode) and rehearsal (practice view measuring time per part, full-script view).
- The page can be reloaded accidentally; current part and time persist in localStorage.

## Capabilities and Constraints

- FIXED RULE: not one word of the spoken text, the questions or the answers may change unless the user rewrites the speech itself (they did once, on 2026-11-24, to detail requirements, limits and scope). Presentation work never edits the text.
- Four diagrams from archify, in Spanish, light mode: Estructura (tree), Recorrido del NNA (workflow), Antes y después (dataflow), Módulos (architecture). They use only facts present in speech.md.
- Spoken text minimum 20px.
- Motion must stop under `prefers-reduced-motion`.
- The note about the authorization letter ("Administración de Consorcios Inmobiliarios") stays at the end of the questions.

## Brand Commitments

Subject: a socio-educational residence (Residencia Socioeducativa Cielo Abierto, SENAF, Córdoba) for children and adolescents under state protection. Tone sober and respectful. No photos of children, ever (the residence itself forbids staff from taking them). No institutional logos are on hand; do not imitate SENAF or government branding.

## Evidence on Hand

- `speech.md` (source text, questions and answers).
- Archify diagrams: `../.archify/*-20261124-164602/*.svg`.
- No photos, logos or other imagery. None may be fabricated.

## Product Principles

1. Glanceable over complete: the current part dominates; everything else recedes.
2. Spoken words are sacred; cues and chrome must never be mistaken for them.
3. Time is the second voice: always visible, quiet when on track, unmistakable when over.
4. Nothing breaks on the day: offline, no build, survives reloads.
5. Sobriety befits the subject.

## Accessibility & Inclusion

Read at arm's length under classroom lighting: high contrast, large type, no reliance on color alone for the over-time warning. Reduced motion respected.
