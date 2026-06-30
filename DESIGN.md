---
name: The Gastronomic Gazette
colors:
  surface: '#fcf9f2'
  surface-dim: '#dcdad3'
  surface-bright: '#fcf9f2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ec'
  surface-container: '#f0eee7'
  surface-container-high: '#ebe8e1'
  surface-container-highest: '#e5e2db'
  on-surface: '#1c1c18'
  on-surface-variant: '#4c4546'
  inverse-surface: '#31312c'
  inverse-on-surface: '#f3f0ea'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#bc0000'
  on-secondary: '#ffffff'
  secondary-container: '#e1281a'
  on-secondary-container: '#fffbff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1b1b'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a8'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#930000'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#fcf9f2'
  on-background: '#1c1c18'
  surface-variant: '#e5e2db'
  paper-base: '#fcf9f2'
  paper-dim: '#f1eee7'
  ink-primary: '#1c1c18'
  ink-muted: '#444748'
  blood-red: '#bc0000'
typography:
  masthead:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '900'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Source Serif 4
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Source Serif 4
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
  label-caps:
    fontFamily: Archivo Narrow
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.08em
  caption:
    fontFamily: Source Serif 4
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
spacing:
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 40px
  column-gap: 24px
  edge-margin: 32px
  rule-weight: 1px
  double-rule-gap: 4px
---

## Brand & Style

The Gastronomic Gazette design system embodies a **Vintage Editorial / Newsprint** aesthetic. It blends the heritage of classical European brasseries with the structured, authoritative layout of a mid-20th-century broadsheet. The brand personality is prestigious, scholarly, and tactile, aiming to evoke the sensory experience of reading a physical newspaper while dining.

Key visual pillars include:
- **Neo-Brutalism (Editorial Variant):** Utilizing heavy black borders, double-rule dividers, and structured vertical lines to create a rigid, informative hierarchy.
- **Tactile Materiality:** Every surface feels like physical paper through the use of subtle textures and halftone patterns.
- **Chronicle Sophistication:** A focus on high-contrast typography and monochromatic imagery with selective color accents to denote luxury and status.

## Colors

The palette is strictly curated to replicate a high-end printed publication.

- **Primary (Ink):** Pure Black (#000000) and Deep Onyx (#1c1c18) serve as the foundation for all structural elements, borders, and main headlines.
- **Secondary (Heritage Red):** A deep, saturated "Blood Red" (#bc0000) is used sparingly for emphasis, price points, and active states, symbolizing the premium nature of the meat.
- **Neutral (Parchment):** The background is not white, but a warm, textured cream (#fcf9f2) that reduces digital eye strain and mimics aged newsprint.
- **Accents:** Halftone dots and subtle grain overlays are used to create depth without introducing new hues.

## Typography

The typographic system uses a "Transitional Serif" pairing to establish authority and legibility.

- **Masthead & Headlines:** `Playfair Display` is used for high-impact titles. It should be used in heavy weights (700-900) to mimic traditional printing presses.
- **Body & Commentary:** `Source Serif 4` provides exceptional readability for long-form descriptions and editorial notes. It should frequently utilize *italic* styles for quotes.
- **System & Utility Labels:** `Archivo Narrow` provides a functional, condensed contrast. It is almost always used in `uppercase` with tracking ranging from 0.08em to 0.2em to create an organized, ledger-like appearance.

## Layout & Spacing

The layout follows a **Rigid Columnar Grid** system inspired by newspaper typesetting.

- **The Grid:** A 12-column layout is preferred for desktop, with a dedicated 3-column "sidebar" for editorial content or indices.
- **Rules & Borders:** Layout sections are separated by `1px` solid black lines. Significant transitions use a "Double Rule" (two parallel 1px lines separated by a 4px gap).
- **Rhythm:** Vertical spacing is generous (`40px` between sections) to allow the "ink" to breathe on the "paper."
- **Responsive Behavior:** On mobile, the sidebar moves to the top of the stack, and margins compress from `32px` to `16px`. Borders remain sharp and consistent across all breakpoints.

## Elevation & Depth

This system rejects digital shadows in favor of **Structural Layering** and **Graphic Depth**:

- **Tonal Depth:** Depth is achieved by varying background shades between the base paper (#fcf9f2) and container parchment (#f1eee7).
- **Halftone Overlays:** A radial gradient pattern (0.5px dots, 3px spacing) is applied to secondary containers to create a tactile "printed" feel.
- **Zero Shadows:** Elevation is never communicated via blurs. Instead, use scale (1.01x on hover) and border-weight changes to indicate interaction.
- **Edge Treatments:** Use "Torn Edge" masks for organic transitions between sections, reinforcing the physical paper metaphor.

## Shapes

The shape language is strictly **Geometric and Sharp**. 

- **Corners:** A `0px` radius is the standard for all containers, buttons, and images to maintain the "cut paper" look.
- **Exceptions:** Miniature data tags or "pills" may use a minimal `2px` (Soft) radius to differentiate functional data from editorial content.
- **Icons:** Use "Material Symbols Outlined" with a weight of 400. Icons should never be filled; they must look like delicate ink illustrations.

## Components

- **The Masthead:** A centralized, high-impact header containing the publication name, issue number, and date, enclosed by double-rule borders.
- **Meat Cards:** Encased in a `1px` black border. They feature a desaturated (grayscale 20%) image that regains full color on hover. Content is divided into headline, description, and a structured nutrition grid.
- **Navigation Links:** Horizontal lists separated by vertical pipes (`|`) in light gray. Active states use a `2px` bottom border in Heritage Red.
- **Data Grids:** Small 3-column modules within cards used for nutritional stats. These use a light gray background and bold condensed labels.
- **Buttons:** Functional buttons are rare; instead, use text links with `Archivo Narrow` and a "hover-to-red" color transition.
- **Editorial Sidebars:** Boxes with a halftone overlay and a high-contrast top border to house secondary information or quotes.