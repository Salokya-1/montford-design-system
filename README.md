# Montford International College — Design System

The brand and design system for **Montford International College**, a Registered
Training Organisation (RTO 46346) and CRICOS-registered provider (04334A) in
Broadmeadows, Melbourne, Australia. We deliver nationally recognised VET
qualifications across Cookery & Hospitality, Health & Community Services, and
Business & Management to domestic and international students.

This repository documents how our brand is built so it can be reproduced
consistently across documents, marketing collateral, the website
([montford.edu.au](https://montford.edu.au)) and digital products.

---

## Colour palette

| Name        | Hex       | Usage                                          |
|-------------|-----------|------------------------------------------------|
| Deep Navy   | `#011F5B` | Primary brand — titles, headings, footer text  |
| Sky Blue    | `#63B3F6` | Accent rules, borders, callout bars            |
| Crimson Red | `#BA0A23` | CTA / alerts (use sparingly)                   |
| Pale Blue   | `#EFF6FE` | Table label / box fills                        |
| Border Blue | `#C9D6E8` | Table cell borders                             |
| Body Ink    | `#1A1A2E` | Table body / value text                        |
| Body Grey   | `#333344` | Callout / box body text                        |
| White       | `#FFFFFF` | Text on navy fills                             |

## Typography

- **Body font:** Segoe UI (Calibri is an acceptable fallback)
- **Body size:** 10pt
- **Heading colour:** Deep Navy `#011F5B`
- **Body colour:** `#3D3D3D` / `#333344`
- **Accent colour:** Sky Blue `#63B3F6`

## Logo

![Montford International College](assets/Montford_Horizontal_Logo.png)

- Always use the **horizontal logo** (`assets/Montford_Horizontal_Logo.png`).
- The logo **already contains** the red `RTO 46346 | CRICOS 04334A` line —
  **never repeat the RTO/CRICOS number anywhere else** in a layout.
- Never stretch, recolour, add shadows, or place a low-resolution copy. The
  aspect ratio is locked.

## Tables

- **Navy text on a pale-blue header fill.** Never use white text on a navy
  header. Cell borders use Border Blue `#C9D6E8`; body text uses Body Ink
  `#1A1A2E`.

## Tone of voice

- Professional, inclusive, plain English suitable for non-native speakers
  (audience: domestic and international students, trainers, admin staff, agents).
- Use correct Australian VET sector terminology.

---

## What's in this repo

```
montford-design-system/
├── README.md                 # This document — the human-readable brand guide
├── tokens/
│   ├── colors.json           # Brand colours as design tokens
│   └── design-tokens.css     # CSS custom properties (variables)
├── assets/
│   └── Montford_Horizontal_Logo.png
└── samples/                  # 56 exported Canva designs (with a gallery index)
    └── README.md             # Visual gallery linking each sample to its live design
```

Use `tokens/design-tokens.css` to pull the palette and type into any web
product, and `tokens/colors.json` as a machine-readable source for build tools.

## Design samples

The [`samples/`](samples/) folder contains exported images of Montford's Canva
designs — flyers, social posts, ID cards, fee sheets and more — as a real-world
reference for how the brand is applied. See the
**[sample gallery](samples/README.md)** for thumbnails linked to each live design.

---

## Organisation details

| Field                | Detail                                                        |
|----------------------|--------------------------------------------------------------|
| RTO ID               | 46346                                                        |
| CRICOS Provider Code | 04334A                                                       |
| ABN                  | 13 669 739 986                                               |
| Campus               | Building AB Ground Floor, 61 Riggall Street, Broadmeadows VIC 3047 |
| Phone                | +61 3 7048 4870                                              |
| Email                | info@montford.edu.au                                         |
| Website              | https://montford.edu.au                                      |
