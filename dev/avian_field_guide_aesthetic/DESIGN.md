---
name: Avian Field Guide Aesthetic
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#414942'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#717971'
  outline-variant: '#c0c9bf'
  surface-tint: '#366848'
  primary: '#134729'
  on-primary: '#ffffff'
  primary-container: '#2d5f3f'
  on-primary-container: '#a1d7ae'
  inverse-primary: '#9dd3ab'
  secondary: '#715a3e'
  on-secondary: '#ffffff'
  secondary-container: '#fdddb9'
  on-secondary-container: '#786044'
  tertiary: '#7c1400'
  on-tertiary: '#ffffff'
  tertiary-container: '#a02910'
  on-tertiary-container: '#ffbaaa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b8efc6'
  primary-fixed-dim: '#9dd3ab'
  on-primary-fixed: '#00210e'
  on-primary-fixed-variant: '#1d5031'
  secondary-fixed: '#fdddb9'
  secondary-fixed-dim: '#e0c29f'
  on-secondary-fixed: '#281803'
  on-secondary-fixed-variant: '#584329'
  tertiary-fixed: '#ffdad3'
  tertiary-fixed-dim: '#ffb4a4'
  on-tertiary-fixed: '#3d0600'
  on-tertiary-fixed-variant: '#8b1a02'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  scientific-name:
    fontFamily: Source Serif 4
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  unit-1: 0.25rem
  unit-2: 0.5rem
  unit-4: 1rem
  unit-6: 1.5rem
  unit-8: 2rem
  unit-12: 3rem
  margin-mobile: 1rem
  margin-desktop: 2.5rem
  gutter: 1rem
---

## Brand & Style
The design system is rooted in the quiet, observant nature of ornithology. It prioritizes clarity, warmth, and a sense of archival preservation. Drawing inspiration from the "Day One" journal and Apple Notes, the interface acts as a neutral but inviting canvas for high-quality photography and field notes.

The style is **Warm Minimalism**. It avoids the sterile coldness of typical tech products by using organic textures and a soft color palette. It feels like a premium physical field guide—organized, authoritative, yet deeply personal. The emotional response should be one of calm focus and scholarly appreciation for nature.

## Colors
The palette is derived from natural landscapes. 
- **Primary (Forest Green):** Used for brand moments, primary actions, and active states. It represents the canopy and deep wilderness.
- **Secondary (Earth Brown):** Used for secondary UI elements, such as metadata tags or scientific classifications.
- **Tertiary (Clay Red):** Reserved for rare bird alerts, high-priority notifications, or distinct progress indicators.
- **Neutral (Warm Off-white):** The foundational background color. It reduces eye strain in outdoor lighting compared to pure white and mimics high-quality recycled paper.
- **Surface:** A slightly darker tint of the neutral background (#F0EDE6) used to differentiate card backgrounds from the main canvas.

## Typography
The typography balances modern readability with classical editorial flair. 
- **Headings:** Use **Plus Jakarta Sans** (a modern alternative to Pretendard with better Latin character support) for a bold, contemporary feel. It provides a clean structure to the "journal" entries.
- **Scientific Names:** Use **Source Serif 4** in italics. This creates a distinct visual hierarchy for Latin bird names, echoing the look of traditional museum catalogs.
- **Body Text:** Plus Jakarta Sans at a medium weight ensures legibility during field use.
- **Captions/Labels:** Small, all-caps labels provide a disciplined, organized look for data points like "Date Spotted" or "GPS Coordinates."

## Layout & Spacing
This design system utilizes a **Fixed Grid** approach for desktop (max-width 1200px) and a **Fluid Grid** for mobile devices. 

- **Vertical Rhythm:** A strict 4px baseline grid ensures consistent alignment of text and icons.
- **Margins:** Generous 24px internal padding within cards creates the "Apple Notes" breathability. 
- **Structure:** Content is organized into a single or double-column feed of cards, mimicking a vertical logbook. On tablet and desktop, the layout expands to a multi-column masonry or grid view to showcase bird photography.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Ambient Shadows** rather than harsh outlines.

- **Level 0 (Canvas):** The warm off-white background (#FAF7F2).
- **Level 1 (Cards):** Pure white (#FFFFFF) or the subtle Surface tint (#F0EDE6) with a very soft, diffused shadow (Blur: 20px, Y: 4, Opacity: 4% Black). This makes cards feel like they are resting lightly on paper.
- **Interactive Elements:** Buttons use a slightly deeper shadow on hover to simulate physical "pressability." 
- **Overlays:** Modals and bottom sheets use a high-blur backdrop filter (glassmorphism) to maintain the context of the natural environment behind the UI.

## Shapes
In line with the organic theme, the design system uses significant rounding. 
- **Standard UI (Buttons, Inputs):** 0.5rem (8px) for a soft but structured look.
- **Container Cards:** 1rem (16px) as the primary roundedness for bird profile cards and journal entries.
- **Image Wrappers:** Always match the container roundedness or use a full "squircle" for profile avatars.
- **Progress Bars:** Fully rounded (pill-shaped) to appear soft and non-technical.

## Components
- **Field Cards:** The primary unit of the UI. Features a large image at the top, followed by a title in Plus Jakarta Sans and the scientific name in Source Serif 4. Soft shadows and 16px corners are mandatory.
- **Nature Icons:** Outlined style with a 1.5pt stroke weight. Terminals should be rounded. Icons should be inspired by natural forms (e.g., a leaf for "Habitat", a feather for "Sighting").
- **Primary Buttons:** Solid Forest Green with white text. High contrast for outdoor visibility.
- **Subtle Progress Bars:** Used for "Collection Completion" or "Song Identification." Use a thin 4px height with a light Earth Brown background and a Forest Green fill.
- **Input Fields:** Minimalist design with only a bottom border or a very light tonal fill. No heavy boxes; focus on the typography.
- **Chips/Tags:** Used for bird traits (e.g., "Migratory," "Forest Dweller"). Use the Surface color (#F0EDE6) with low-contrast text to keep them secondary to the main content.