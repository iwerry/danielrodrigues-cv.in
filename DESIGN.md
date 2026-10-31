---
name: Daniel Rodrigues Portfolio
description: Existing editorial, kinetic, multilingual portfolio visual system
colors:
  light-bg: "#eef0ff"
  light-text: "#0a0b2e"
  light-blue: "#1d21ff"
  light-muted: "#4a4d7a"
  dark-bg: "#07082b"
  dark-text: "#eceeff"
  dark-blue: "#6f74ff"
  dark-muted: "#a3a7dd"
typography:
  display:
    fontFamily: "Big Shoulders Display, Arial Narrow, Impact, sans-serif"
    fontWeight: 900
  body:
    fontFamily: "Newsreader, Georgia, serif"
    fontSize: "1.125rem"
    lineHeight: 1.6
rounded:
  card: "8px"
  photo: "6px"
  control: "99px"
---
## Overview
Expressive, typographic UX/UI portfolio. This document describes the incumbent code, not an independently approved redesign.

## Colors
Color scheme adapts to light and dark using CSS variables in index.html. Electric blue is the central brand accent.

## Typography
Big Shoulders Display anchors display headlines, controls and card headings; Newsreader carries body copy and editorial text.

## Layout
Full-viewport WebGL hero, maximum 1300px sections, responsive card grid and two-column About/education; breakpoints include 760px and 700px.

## Elevation & Depth
Grid shader and card tilt/spotlight create movement; reserve motion for nonessential visual feedback.

## Shapes
Mostly sharp editorial rectangles with smaller radius on cards; controls use pill silhouettes, portrait mask is cropped.

## Components
Header navigation with language and theme controls; project cards open external links; biography image; skill chips; timeline; contact CTAs. Focus-visible outline is defined in base CSS.

## Do's and Don'ts
- Retain typographic brand and projects verified through public work.
- Do not block navigation on mobile or keyboard.
- Never claim a completed bachelor's degree.
- Avoid adding decorative effects before readability and interaction tests.
