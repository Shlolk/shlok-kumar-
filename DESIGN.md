---
name: Obsidian Flux
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
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#849495'
  outline-variant: '#3a494b'
  surface-tint: '#00dbe7'
  primary: '#e1fdff'
  on-primary: '#00363a'
  primary-container: '#00f2ff'
  on-primary-container: '#006a71'
  inverse-primary: '#00696f'
  secondary: '#c6c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#484949'
  on-secondary-container: '#b8b8b8'
  tertiary: '#f7f8f8'
  on-tertiary: '#2f3131'
  tertiary-container: '#dbdbdb'
  on-tertiary-container: '#5e6060'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#74f5ff'
  primary-fixed-dim: '#00dbe7'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-2xl:
    fontFamily: Hanken Grotesk
    fontSize: 120px
    fontWeight: '800'
    lineHeight: 110px
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.2em
  mono-code:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style

The design system is engineered for an elite developer persona, merging the clinical precision of high-end hardware with the immersive atmosphere of high-fidelity sci-fi cinema. The aesthetic is a fusion of **Glassmorphism** and **High-Contrast Minimalism**, utilizing "Dark Mode" as the foundational canvas rather than an alternative theme. 

The target audience is high-stakes tech recruiters, luxury brand collaborators, and fellow engineers who value technical mastery and avant-garde design. The UI must evoke a sense of "The Future, Delivered": a world where code is tangible, interfaces are ethereal, and every interaction feels like manipulating a sophisticated piece of sentient machinery.

**Key Visual Pillars:**
- **Kinetic Depth:** Using layering and optical blurs to create a multi-dimensional workspace.
- **Luminescent Accents:** Using vibrant cyan light as a functional signifier for interactivity and progress.
- **Architectural Typography:** Treating text as a structural element, using extreme scale and generous tracking to command attention.

## Colors

The palette is rooted in absolute darkness to maximize the "pop" of luminescent elements.

- **Background (#000000):** Used for the primary viewport to ensure infinite depth.
- **Surface (#0a0a0a):** A deep charcoal used for elevated cards and containers to create subtle separation from the void.
- **Electric Cyan (#00f2ff):** The "Flux" color. Used sparingly for primary actions, focus states, and data visualizations. It should often be accompanied by a soft glow effect.
- **Metallic Silver (#c0c0c0):** Used for secondary text and decorative borders, providing a cool, premium industrial feel.
- **Pure White (#ffffff):** Reserved for high-priority display text and critical readability.

## Typography

The typographic hierarchy relies on extreme contrast in scale and weight. **Hanken Grotesk** provides a sharp, modern edge for headlines, while **Inter** ensures perfect readability for technical descriptions. **Geist** is utilized for metadata and code snippets to reinforce the developer-centric nature of the design system.

**Usage Rules:**
- **Wide Tracking:** Apply `label-caps` to all sub-headers and category tags to create an editorial, luxury feel.
- **Negative Kerning:** For `display-2xl` and `display-lg`, use negative letter spacing to create a tight, impactful visual block.
- **Gradient Text:** Use a vertical gradient from `#ffffff` to `#c0c0c0` on large headlines to simulate a metallic sheen.

## Layout & Spacing

This design system employs a **Fluid Grid** with generous white space (or "black space") to allow elements to breathe and feel intentional. 

- **The Void:** Layouts should prioritize large, empty margins to draw focus toward centered content.
- **Grid:** Use a 12-column grid for desktop. Content blocks should typically span 6-8 columns to avoid excessive line lengths.
- **Sectioning:** Use large vertical gaps (`section-gap`) between content blocks to create a "scrolling gallery" experience where each section feels like a new cinematic scene.
- **Alignment:** Use a mix of center-aligned hero sections and strictly left-aligned technical data to balance art and utility.

## Elevation & Depth

Depth is not communicated via traditional shadows, but through **Luminance and Refraction**.

- **Level 1 (Base):** Pure Black background (#000000).
- **Level 2 (Containers):** Deep Charcoal (#0a0a0a) with a 1px border of `rgba(255, 255, 255, 0.1)`.
- **Level 3 (Glass):** Semi-transparent surfaces using `backdrop-filter: blur(20px)` and a thin gradient stroke that mimics light catching the edge of a glass pane.
- **Ambient Lighting:** Use large, low-opacity radial gradients (blobs) of Cyan (#00f2ff) behind key cards or sections to create a "glow from within" effect. This simulates hardware LEDs reflecting off a dark surface.

## Shapes

The shape language is sophisticated and controlled. We avoid fully organic circles in favor of "Squiggles" or refined rectangles.

- **Containers:** Use `rounded-lg` (8px) for cards and main UI elements. This provides a modern touch without appearing "bubbly."
- **Interactive Elements:** Buttons and tags use a slightly tighter `rounded` (4px) to maintain a technical, sharp-edged feel.
- **Gradients Borders:** Use a subtle linear gradient on borders (from `white/20%` to `transparent`) to give shapes a 3D glass effect.

## Components

### Buttons
- **Primary:** Solid Cyan (#00f2ff) with black text. Apply a `box-shadow` with a cyan blur to create a neon glow effect on hover.
- **Secondary:** Ghost style with a 1px Silver (#c0c0c0) border. On hover, the border becomes White and the background gains a slight `white/5%` tint.

### Cards
- **Project Cards:** Glassmorphic background with a subtle "noise" texture overlay. Ensure the top border is slightly brighter than the bottom to simulate top-down lighting.
- **Tech Stacks:** Represented as small, high-contrast badges using the `mono-code` font style.

### Inputs
- **Text Fields:** Minimalist bottom-border only, or a dark charcoal filled box. The focus state should animate the border color to Cyan and trigger a subtle outer glow.

### Navigation
- **Header:** A floating, blurred glass bar that sits at the top of the viewport. Use `label-caps` for nav links with a high-contrast active state.

### Interactive "Flux" Elements
- **Scroll Progress:** A thin, 2px Cyan line at the very top of the screen.
- **Cursors:** A custom circular cursor that expands when hovering over interactive elements, changing from a simple dot to a hollow ring.