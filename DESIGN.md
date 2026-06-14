---
name: Nocturne Editorial
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c9c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#d0cecd'
  on-tertiary: '#313030'
  tertiary-container: '#b5b2b2'
  on-tertiary-container: '#454545'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 84px
    fontWeight: '600'
    lineHeight: 92px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 38px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
  caption:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
spacing:
  container-max: 1440px
  edge-margin-desktop: 80px
  edge-margin-mobile: 24px
  gutter: 32px
  section-gap: 160px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built for high-end visual storytelling, evoking the atmosphere of a premium fashion monograph. The personality is sophisticated, exclusive, and quiet, allowing the photography to command the narrative. 

The design style is **Cinematic Minimalism** mixed with **High-Contrast Editorial** elements. It prioritizes "blackspace" over whitespace to create a sense of depth and prestige. The interface serves as a dark gallery frame—unobtrusive but structurally rigorous. Interaction should feel deliberate and fluid, utilizing thin strokes and expansive layouts to suggest a luxury physical print experience.

## Colors

The palette is anchored in deep, cinematic blacks to provide maximum contrast for photographic work. 

- **Primary (Antique Gold):** Used sparingly for interactive accents, active states, and critical branding elements. It should feel like a foil-stamped detail on a book cover.
- **Background (Deep Charcoal):** The primary canvas. It is deep enough to disappear, focusing the eye on the content.
- **Secondary Background (Rich Black):** Used for structural depth, such as navigation bars, footers, or nested card elements.
- **Neutral (Soft White):** Used for primary typography to ensure legibility without the harshness of pure #FFFFFF.
- **Secondary Text (Warm Gray):** Used for metadata, captions, and de-emphasized information.

## Typography

The typography strategy relies on the tension between the expressive, high-contrast serifs of the headlines and the clinical, understated clarity of the sans-serif body text.

- **Headlines:** Use Playfair Display for all major headings. It should be set with tight letter-spacing for large display sizes to emphasize its editorial roots.
- **Body:** DM Sans provides a neutral, modern counterpoint. It ensures that long-form descriptions or artist statements remain highly readable against dark backgrounds.
- **Metadata:** Use the `label-caps` style for navigation, category tags, and dates. The wide tracking (letter-spacing) adds an architectural feel to the UI.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid Grid**. Content is housed within a 12-column grid with generous margins to simulate the "gutters" of a high-end magazine.

- **Whitespace (Blackspace):** Use expansive vertical padding (`section-gap`) between portfolio projects to allow each piece to breathe.
- **Asymmetry:** Encourage asymmetrical placements for images (e.g., spanning columns 2-10 or 1-7) to break the standard "website" feel and lean into a curated look.
- **Responsive Behavior:** On mobile, margins reduce to 24px and the grid collapses to a single column, but the oversized typography remains impactful, scaling down only as much as necessary for legibility.

## Elevation & Depth

This design system avoids traditional shadows to maintain a flat, modernist aesthetic. Depth is communicated through **Tonal Layering** and **Thin Accents**.

- **Surface Tiers:** The base level is #0B0B0B. Overlays or secondary modules use #111111.
- **Outlines:** Instead of shadows, use "Ghost Borders"—1px solid strokes in Antique Gold (#D4AF37) at low opacity (15-20%) or Rich Black (#111111) for subtle containment.
- **Interaction Depth:** Hover states on images should use a slight scale-up (1.02x) combined with a subtle desaturation or brightness shift rather than a shadow.

## Shapes

The shape language is **strictly geometric and sharp**. Rounded corners are avoided to maintain the architectural and "printed" feel of the portfolio.

- **Images:** All photographs must have 0px border radius.
- **Buttons & Inputs:** Use sharp 90-degree angles.
- **Dividers:** Horizontal and vertical lines should be 1px thin, using the Antique Gold color at 30% opacity to create a framework that feels like fine jewelry or wireframes.

## Components

### Buttons
- **Primary:** No background fill. 1px solid Antique Gold border. Text in `label-caps` gold. On hover, the background fills with Antique Gold and text switches to Rich Black.
- **Text Link:** Simple `label-caps` with a 1px underline that expands from the center on hover.

### Cards & Gallery Items
- **Image Container:** Fixed aspect ratios (4:5 or 3:2). No padding within the card.
- **Captions:** Placed either directly below the image in `caption` style or appearing as a subtle overlay on hover.

### Inputs
- **Field Styling:** Bottom-border only (1px Soft White). Background is transparent.
- **Labels:** `label-caps` positioned above the input.

### Navigation
- **Header:** Transparent background that blurs slightly or turns to Rich Black on scroll.
- **Links:** Minimalist `label-caps` with generous horizontal spacing (40px+).

### Lists
- **Project List:** Large-scale typography (`headline-lg`) that reveals an image thumbnail on hover. Separated by 1px dimmed gold dividers.