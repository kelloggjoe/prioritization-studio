---
name: Prioritization Studio
description: A warm, tactile decision workspace for making roadmap tradeoffs visible.
colors:
  paper: "#fdfcf8"
  surface: "#fffefa"
  ink: "#2c2c24"
  muted: "#68685e"
  moss: "#5d7052"
  moss-dark: "#41503a"
  clay: "#b9784e"
  sand: "#e6dccd"
  stone: "#f0ebe5"
  timber: "#d7cfc4"
typography:
  display:
    fontFamily: "Fraunces, serif"
    fontSize: "clamp(3rem, 6.7vw, 6.2rem)"
    fontWeight: 700
    lineHeight: 0.94
    letterSpacing: "-0.035em"
  body:
    fontFamily: "Nunito, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.6
rounded:
  control: "999px"
  panel: "24px"
  organic: "38px 22px 42px 24px"
spacing:
  sm: "8px"
  md: "16px"
  lg: "24px"
components:
  button-primary:
    backgroundColor: "{colors.moss}"
    textColor: "#ffffff"
    rounded: "{rounded.control}"
    padding: "11px 19px"
  panel:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "24px"
---

# Design System: Prioritization Studio

## Overview

**Creative North Star: "The Planning Table"**

Prioritization Studio feels like a calm working session around a well-used planning table: tactile, grounded, and human without compromising operational clarity. Organic silhouettes and warm earth colors soften a dense scoring task, while consistent controls keep the interface trustworthy.

**Key Characteristics:** warm paper surfaces; moss and clay accents; asymmetric but restrained forms; generous breathing room; clear numeric hierarchy.

## Colors

Moss carries action and scoring, clay marks secondary interaction, and warm neutrals separate working layers.

**The Earthbound Signal Rule.** Saturated color is reserved for actions, weights, and decision signals; content surfaces stay warm and quiet.

## Typography

**Display Font:** Fraunces (serif)  
**Body Font:** Nunito (system sans fallback)

Fraunces gives propositions and section titles a crafted editorial voice. Nunito keeps controls, labels, and data friendly and highly legible.

## Layout

The desktop workspace uses a 300px weights rail beside a flexible initiative table. At 850px the rail and roadmap stack; at 600px the table becomes two-column initiative cards. The container is capped at 1320px with 16px minimum outer gutters.

## Elevation & Depth

Depth is ambient and moss-tinted. Panels use a soft `0 18px 48px -28px rgba(93,112,82,.48)` shadow; controls use smaller shadows and a short upward hover response.

## Shapes

Pills are reserved for controls and numeric inputs. Panels use asymmetric 20–44px corner combinations, while identity marks and scores use specific organic silhouettes. The irregularity is deliberate but never applied to data alignment.

## Components

- **Buttons:** 46px minimum height, pill shape, moss primary and clay outline secondary.
- **Panels:** warm-white surfaces, timber hairline boundaries, ambient elevation.
- **Inputs:** quiet translucent fills with pill or soft 18px corners and moss focus borders.
- **Ranks:** compact sand-colored organic markers with tabular ordering.

## Do's and Don'ts

### Do:
- **Do** preserve a calm, tactile hierarchy around a dense decision task.
- **Do** use Fraunces for propositions and Nunito for operation.
- **Do** keep mobile initiative cards fully editable without horizontal scrolling.

### Don't:
- **Don't** introduce violet, neon accents, or hard offset shadows.
- **Don't** use decorative texture overlays; shape, color, and spacing carry the material character.
- **Don't** let organic shapes reduce numeric scanability.
