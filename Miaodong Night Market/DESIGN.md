---
name: Taiwanese Retro Modern
colors:
  surface: '#fef9f1'
  surface-dim: '#ded9d2'
  surface-bright: '#fef9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3eb'
  surface-container: '#f2ede6'
  surface-container-high: '#ede7e0'
  surface-container-highest: '#e7e2db'
  on-surface: '#1d1b17'
  on-surface-variant: '#59413e'
  inverse-surface: '#32302c'
  inverse-on-surface: '#f5f0e9'
  outline: '#8d706d'
  outline-variant: '#e1bfba'
  surface-tint: '#b12c25'
  primary: '#8e0f0f'
  on-primary: '#ffffff'
  primary-container: '#b02b24'
  on-primary-container: '#ffcbc5'
  inverse-primary: '#ffb4aa'
  secondary: '#835400'
  on-secondary: '#ffffff'
  secondary-container: '#fdb244'
  on-secondary-container: '#6e4600'
  tertiary: '#5e3e3b'
  on-tertiary: '#ffffff'
  tertiary-container: '#795552'
  on-tertiary-container: '#fcccc9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#8f1010'
  secondary-fixed: '#ffddb5'
  secondary-fixed-dim: '#ffb956'
  on-secondary-fixed: '#2a1800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#eabcb8'
  on-tertiary-fixed: '#2e1413'
  on-tertiary-fixed-variant: '#5f3e3c'
  background: '#fef9f1'
  on-background: '#1d1b17'
  surface-variant: '#e7e2db'
typography:
  headline-xl:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Noto Serif
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Noto Serif
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Noto Serif
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
spacing:
  unit: 4px
  gutter: 24px
  margin: 32px
  container-max-width: 1200px
---

## Brand & Style
This design system captures the soulful essence of a bustling Taiwanese night market through a lens of contemporary refinement. It balances the "Old Soul" (老靈魂) of traditional street commerce with a clean, structured digital architecture.

The design style is **Tactile Retro-Modern**. It leverages physical metaphors from mid-century Taiwanese architecture—specifically the warmth of terrazzo floors, temple lacquerware, and the editorial rhythm of vintage broadsheets. The aesthetic goal is to evoke nostalgia (懷舊) without feeling dated, using high-contrast color pairings and rigid "double-line" framing to keep the dense content of a night market directory feeling organized and premium.

**Emotional Response:**
- **Nostalgic:** Familiarity through textures and color.
- **Vibrant:** Capturing the energy of food stalls and neon signage.
- **Authentic:** Grounded in local cultural markers like temple reds and golden-brown delicacies.

## Colors
The palette is derived from the material culture of Taiwan. 

- **Global Background (Terrazzo Grey - #DCD7D0):** A warm, desaturated neutral that mimics aged stone and paper. It provides a low-strain foundation for long-form reading.
- **Primary/Titles (Tzu Chi Temple Red - #B02B24):** A deep, authoritative red used for branding and primary headings, reminiscent of temple pillars and traditional lanterns.
- **Accent/Buttons (Water Chestnut Cake Gold - #F2A93B):** A high-visibility, savory yellow-gold used for interactive elements and highlights.
- **Body Text (Deep Chestnut Wood - #4A2C2A):** A dark, earthy brown that provides better legibility and a softer "vintage" feel compared to pure black.

## Typography
The typographic system mimics the high-density editorial style of 1960s Taiwanese newspapers and temple signage.

- **Headlines:** Use **Newsreader** in bold/extra-bold weights. The tight line heights and high-contrast serifs reflect the "Bold Serif" look of traditional Chinese signage.
- **Body & Labels:** Use **Noto Serif**. This maintains a "Ming-style" (明體) aesthetic which is more literary and nostalgic than sans-serif alternatives.
- **Stylistic Note:** For vertical headers or decorative text, apply a 90-degree rotation to mimic traditional vertical script found on street banners.

## Layout & Spacing
The layout follows a **Fixed Grid** model to maintain the structured look of a printed directory. 

- **Grid:** A 12-column system with substantial 24px gutters.
- **Double-Line Borders:** Major sections are defined by a "One thick, one thin" border (e.g., a 2px outer line and a 1px inner line with 2px of spacing between them) using the 'Deep Chestnut Wood' color.
- **Rhythm:** Generous vertical padding (64px+) between sections to allow the textures and photography to breathe, preventing the "night market" density from becoming overwhelming.

## Elevation & Depth
This design system avoids modern ambient shadows in favor of **Tonal Layers** and **Bold Borders**. 

- **Physicality:** Depth is communicated through paper-like overlays. Surfaces are differentiated by shifting from 'Terrazzo Grey' to a slightly lighter off-white or a subtle tile pattern background.
- **Micro-patterns:** Use a 5% opacity "Floral Tile" or "Cross-hatch" micro-pattern on secondary surfaces to create tactile interest.
- **No Floating:** Elements should feel "pressed" or "printed" onto the background rather than floating above it. Use 1px or 2px solid borders in 'Deep Chestnut Wood' to define cards and containers.

## Shapes
The shape language is **Strictly Geometric (Sharp)**. 

To maintain the architectural and "newspaper" feel, all buttons, containers, and image masks use 0px border-radius. The only exception is the use of circular "Stamps" or "Seals" for status indicators (e.g., "Open Now"), which should mimic traditional red ink chops.

## Components

- **Buttons:** Sharp corners. Primary buttons use 'Water Chestnut Cake Gold' background with 'Deep Chestnut Wood' text. Use a 1px solid border. Hover states should shift the background to a slightly more saturated gold.
- **Cards (Food/Stalls):** Use the signature "one thick, one thin" double-line border for the container. Images should occupy the top half with high-saturation, warm-lit photography.
- **Chips/Labels:** Small, rectangular boxes with a solid 'Tzu Chi Temple Red' background and white/cream text, resembling price tags or stall markers.
- **Inputs:** Simple bottom-border only (like a fill-in-the-blank form) or a full border with a subtle paper texture background.
- **Photography Style:** All imagery must feature warm white balance, visible steam/smoke from food, and high saturation to capture the "heat" of the market.
- **Special Component: "The Red Chop":** A circular decorative element used for "Sold Out" or "Recommended" tags, using a rough-edged stamp texture in 'Tzu Chi Temple Red'.