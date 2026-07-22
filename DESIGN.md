---
name: Lumina Nexus
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#c9c3da'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#938ea3'
  outline-variant: '#484457'
  surface-tint: '#c9beff'
  primary: '#c9beff'
  on-primary: '#30009b'
  primary-container: '#5d26ff'
  on-primary-container: '#dad1ff'
  inverse-primary: '#5e2aff'
  secondary: '#e6feff'
  on-secondary: '#003739'
  secondary-container: '#00f4fe'
  on-secondary-container: '#006c71'
  tertiary: '#ffb59d'
  on-tertiary: '#5d1900'
  tertiary-container: '#a93400'
  on-tertiary-container: '#ffcbba'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e6deff'
  primary-fixed-dim: '#c9beff'
  on-primary-fixed: '#1b0062'
  on-primary-fixed-variant: '#4600d7'
  secondary-fixed: '#63f7ff'
  secondary-fixed-dim: '#00dce5'
  on-secondary-fixed: '#002021'
  on-secondary-fixed-variant: '#004f53'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59d'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832600'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
  electric-blue: '#2E5BFF'
  neon-purple: '#8A2BE2'
  hot-pink: '#FF1493'
  coral-orange: '#FF7F50'
  emerald-green: '#50C878'
  aqua-cyan: '#00FFFF'
  bright-yellow: '#FCE205'
  lavender: '#E6E6FA'
  glass-stroke: rgba(255, 255, 255, 0.12)
typography:
  display-xl:
    fontFamily: sora
    fontSize: 96px
    fontWeight: '800'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  display-lg:
    fontFamily: sora
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: sora
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: jetbrainsMono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1440px
  margin-desktop: 80px
  margin-mobile: 24px
  gutter: 32px
  stack-xl: 160px
  stack-md: 80px
---

## Brand & Style

The design system is engineered for an **AI Engineer and Creative Technologist**, merging technical precision with breathtaking digital artistry. The brand personality is "Techno-Optimist"—intellectual yet vibrant, sophisticated yet playful. It aims to evoke a sense of wonder and "functional magic," positioning the portfolio not just as a resume, but as an immersive digital universe.

The visual style is a hybrid of **Glassmorphism** and **Futuristic Expressive**. It leverages high-fidelity blurs, holographic textures, and vibrant aurora gradients to create depth. Taking cues from Nothing.tech’s industrial minimalism and Stripe’s fluid color transitions, the interface feels like a physical light-based OS floating in a dark vacuum. This design system prioritizes motion and light as the primary vehicles for storytelling.

## Colors

The system uses a **Dark Mode** foundation to maximize the luminosity of its vibrant accent palette. The base surface is a deep, near-black neutral (#0A0A0B), which acts as the "void" for the "AI Universe."

Each section of the portfolio is anchored by a dominant "Aurora Core" color, but all elements share a cohesive glassmorphic treatment. 
- **Primary & Secondary:** Used for high-level branding, active states, and primary interactive nodes.
- **Named Colors:** Used to differentiate thematic sections (e.g., Pink for "Creative," Cyan for "Engineering").
- **Holographic Gradients:** Gradients should never be static. They must utilize multi-stop mesh gradients combining at least three named colors to create a liquid, shifting effect.

## Typography

The typography strategy balances high-impact display faces with technical utility.
- **Headlines:** Sora provides a geometric, futuristic feel. Large headlines should implement **independent letter animations** (e.g., staggered vertical slides or opacity fades) to enhance the "Awwwards" level interactivity.
- **Body:** Inter is used for its exceptional readability and neutral "pro" aesthetic, ensuring complex AI technical descriptions remain legible.
- **Labels/Data:** JetBrains Mono is used for GitHub stats, technical specs, and metadata to reinforce the Engineering identity of the brand.

## Layout & Spacing

This design system utilizes a **Fluid Grid** with generous vertical "breathing room" to create a premium, gallery-like experience. 
- **The Flow:** Content should follow a "Z-pattern" or "Center-Focus" layout to allow background aurora effects to remain visible.
- **Micro-Layouts:** Use a 12-column grid for desktop, but allow elements like "Planetary Nodes" to break the grid to create a sense of organic, floating space.
- **Breakpoints:** 
  - **Desktop (1440px+):** Full 80px margins, 160px section spacing.
  - **Tablet (768px - 1024px):** 40px margins, 100px section spacing.
  - **Mobile (<768px):** 24px margins, 80px section spacing; stack all multi-column layouts into single columns.

## Elevation & Depth

Hierarchy is established through **Luminous Layering** rather than traditional shadows.
- **Base:** The deepest layer is the dark neutral background with blurred "Glowing Blobs" moving slowly.
- **Mid-Ground (The Glass):** Cards and panels use a backdrop-filter (blur: 20px) and a semi-transparent fill (rgba(255, 255, 255, 0.03)). 
- **Fore-Ground (The Light):** Interactive elements use "Inner Glows" and "Holographic Reflections." 
- **Strokes:** Use 1px "Ghost Borders"—thin, low-opacity white lines—to define shapes without adding visual bulk. On hover, these borders should transition to a gradient stroke matching the section's dominant color.

## Shapes

The shape language is primarily **Rounded (0.5rem - 1.5rem)** to maintain a soft, approachable feel amidst the technical complexity. 
- **Interactive Elements:** Buttons and small chips use high roundedness (pill-shaped) to invite clicking.
- **The "Morph":** Specialized containers for AI demos should utilize SVG filters to "morph" between organic, liquid shapes and structured rectangles during state transitions. 
- **Skill Nodes:** These are perfect circles, behaving like planetary bodies with varying sizes based on proficiency.

## Components

- **Magnetic Buttons:** Primary CTAs should have a "magnetic" effect where the label subtly follows the cursor. They feature a 1px glowing border that activates on hover.
- **Holographic Cards:** Portfolio project cards must use a 3D tilt effect (tilt-js style) where the highlight/reflection moves in opposition to the mouse, creating a "glass sheet" illusion.
- **Planetary Nodes:** Circular skill indicators with an outer "orbit" ring. The ring's dash-array should represent the level of expertise.
- **Data Panels:** For GitHub/Technical stats, use semi-transparent panels with monospaced text and "scanline" overlays (fine horizontal lines at 5% opacity).
- **Floating Navigation:** A docked, glassmorphic pill at the bottom or top of the viewport that changes its accent color based on the current scroll section.
- **Liquid Transitions:** Use WebGL or CSS clip-path transitions between sections to simulate "zooming through a portal" rather than standard scrolling.