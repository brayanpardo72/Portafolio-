---
name: Technical Precision Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c1c6d7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8b90a0'
  outline-variant: '#414755'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e69'
  primary-container: '#4b8eff'
  on-primary-container: '#00285c'
  inverse-primary: '#005bc1'
  secondary: '#c6c6cb'
  on-secondary: '#2f3034'
  secondary-container: '#46464b'
  on-secondary-container: '#b5b4ba'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#909191'
  on-tertiary-container: '#282a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#e3e2e7'
  secondary-fixed-dim: '#c6c6cb'
  on-secondary-fixed: '#1a1b1f'
  on-secondary-fixed-variant: '#46464b'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
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
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is engineered for a dual-discipline professional at the intersection of Civil Engineering and Data Science. It balances the structural weight of engineering with the digital fluidity of data analytics. The aesthetic is rooted in **Premium Dark Mode**, drawing inspiration from high-end technology leaders like Apple and Tesla.

The style is a fusion of **Corporate Modernism** and **Glassmorphism**. It utilizes deep obsidian surfaces, ultra-refined typography, and translucent layers to convey a sense of depth and architectural integrity. The emotional response should be one of "Expertise and Innovation"—suggesting a practitioner who is as comfortable with physical blueprints as they are with neural networks. High-contrast elements ensure data is readable, while subtle motion and 3D card effects suggest a sophisticated, forward-thinking approach to academic research.

## Colors

The palette is strictly curated to evoke the atmosphere of a high-tech laboratory or a modern architectural studio.

- **Primary (Electric Blue):** Used sparingly for interactive elements, data visualization highlights, and primary calls to action. It represents the "spark" of innovation.
- **Secondary (Slate Gray):** Utilized for secondary text, borders, and icon outlines. It provides the necessary nuance between the background and the foreground.
- **Tertiary (Pure White):** Reserved for high-priority headlines and key data points to ensure maximum legibility against the dark canvas.
- **Neutral (Deep Charcoal):** The foundation of the UI. This is not a flat black, but a rich charcoal that allows for softer shadows and better depth perception.

Backgrounds should utilize a slight radial gradient from the center (#161616) to the edges (#0B0B0B) to create a subtle sense of spotlighting content.

## Typography

The typography uses **Inter**, a typeface designed for screens, providing a systematic and utilitarian feel that aligns with data science precision. 

Large display titles should use heavy weights with tight letter-spacing to mimic the editorial feel of luxury tech branding. Body text remains generous in line-height to ensure that long-form academic research descriptions remain accessible. Label styles are set in uppercase with increased letter-spacing to serve as structural markers throughout the interface, reminiscent of engineering technical drawings.

## Layout & Spacing

This design system follows a **Fixed Grid** approach for desktop to maintain a "gallery" feel, where content is curated within a centered 1200px container. 

- **Grid:** A 12-column grid is used for desktop, 8 columns for tablet, and 4 columns for mobile.
- **Rhythm:** An 8px base unit drives all padding and margin decisions. 
- **Sectioning:** Large vertical gaps (120px+) between major sections create a sense of prestige and allow the user to focus on one project or research area at a time.
- **Responsive Behavior:** On mobile, margins tighten significantly, and complex 3D card layouts should stack vertically into a single-column view while maintaining the same 8px-based internal padding.

## Elevation & Depth

Depth is the primary driver of hierarchy in this design system. It is achieved through **Glassmorphism** and multi-layered surface stacking:

1.  **Level 0 (Base):** The Deep Charcoal background.
2.  **Level 1 (Card):** A semi-transparent surface (Approx 40% opacity) with a `backdrop-filter: blur(20px)`. Borders are thin (1px) and use a top-down linear gradient from White (10% opacity) to White (0% opacity) to simulate a light source hitting the top edge.
3.  **Level 2 (Interactive/Floating):** Higher blur (40px) and a subtle outer glow using the Primary Electric Blue at very low opacity (5-10%).

**3D Card Effects:** Cards should utilize a subtle tilt on hover, combined with a moving specular highlight (a white gradient mask) that follows the cursor, giving the interface a physical, high-tech feel.

## Shapes

The shape language is "Modern-Rounded." Corners are soft enough to feel approachable but sharp enough to remain professional.

- **Base Radius (0.5rem):** Applied to standard input fields and small buttons.
- **Large Radius (1rem):** Applied to project cards and containers.
- **Extra Large (1.5rem):** Used for large featured hero elements or parent containers that house nested cards.

All shapes must maintain their aspect ratios during transitions to ensure the "engineering precision" is felt in the motion design.

## Components

### Buttons
- **Primary:** Solid Electric Blue with white text. On hover, a subtle "inner glow" effect.
- **Secondary:** Glass-style with a thin white border. Background is transparent with a backdrop blur.
- **Tertiary:** Text-only with an arrow icon that translates 4px to the right on hover.

### Cards (The "Research" Card)
The core component of this system. These feature a glass background, high-contrast typography, and a subtle 3D tilt. If the card contains an image (e.g., a civil engineering project), the image should be placed behind the glass layer with a "soft mask" to blend into the charcoal background.

### Data Inputs
Input fields are dark with a 1px border that glows Electric Blue when focused. Labels always sit above the field in the `label-sm` style.

### Chips & Tags
Small, pill-shaped markers used for "Skills" or "Technologies." These use a Slate Gray background with 10% opacity and a solid Slate Gray border to keep them secondary to the main content.

### Progress Indicators
For data science projects, use "thin-line" loaders or progress bars in Electric Blue. The motion should be a smooth "ease-in-out" to match the premium feel of the system.