---
version: alpha
name: Barbershop de Rijn — Light Premium
description: Premium barbershop stijl op basis van klantfeedback ("zoiets maar lichter, niet donker"). Licht, elegant, minimalistisch.
colors:
  primary: "#1a1a1a"
  accent: "#b08d57"
  neutral: "#fbfaf7"
  neutralDark: "#2a2a2a"
  textMuted: "#6b6b6b"
typography:
  h1:
    fontFamily: Cormorant Garamond
    fontSize: 3.5rem
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  body:
    fontFamily: Inter
    fontSize: 1rem
    lineHeight: 1.6
rounded:
  sm: 6px
  md: 10px
  lg: 16px
spacing:
  sm: 12px
  md: 24px
  lg: 48px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "#FFFFFF"
    rounded: "{rounded.sm}"
    padding: 14px 28px
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    rounded: "{rounded.sm}"
    padding: 14px 28px
---

## Overview

LICHTE premium barbershop. Klant (Ozemarov) gaf expliciet aan: Empire-stijl
premium look, maar LICHT — "dit is te donker". Donkere achtergronden zijn
uitgesloten. Warm ivoor/crème achtergrond, donkere tekst, subtiel goud accent.

## Colors

- **Primary (#1a1a1a):** Donker voor headings en knoppen.
- **Accent (#b08d57):** Warm goud — spaarzaam, alleen voor logo-detail en
  subtiele highlights. NOOIT als volledige achtergrond.
- **Neutral (#fbfaf7):** Warm ivoor — de hoofdkleuren achtergrond. Altijd licht.
- **textMuted (#6b6b6b):** Grijze bodytekst.

## Typography

- Cormorant Garamond (serif) voor headings — elegant, klassiek.
- Inter (sans) voor body — leesbaar, modern.
- "de Rijn" in het logo mag italic/goud voor premium detail.

## Layout & Spacing

- Veel witruimte — luxe gevoel.
- Centered hero, lichte secties afgewisseld met subtiel crème.

## Components

- `button-primary`: donker op lichte achtergrond (contrast).
- `button-secondary`: outline, transparant.

## Do's and Don'ts

- ✅ LICHTE achtergrond (ivoor/crème/wit)
- ✅ Serif headings + gouden detail
- ❌ Donkere achtergrond (klant zei "te donker")
- ❌ Felle accentkleuren (geen rood/oranje dominant)
- ❌ Meer dan 1 accentkleur
