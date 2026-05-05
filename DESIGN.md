---
name: Atelier Kopec
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#49473f'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#7a776f'
  outline-variant: '#cbc6bc'
  surface-tint: '#615e58'
  primary: '#615e58'
  on-primary: '#ffffff'
  primary-container: '#f5f0e8'
  on-primary-container: '#6f6d67'
  inverse-primary: '#cac6be'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#aa3600'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffede8'
  on-tertiary-container: '#c0430d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7e2da'
  primary-fixed-dim: '#cac6be'
  on-primary-fixed: '#1d1c17'
  on-primary-fixed-variant: '#494741'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59c'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#822800'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-xl:
    fontFamily: Noto Serif
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  section-padding: 120px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

The design system is rooted in the aesthetic of high-end architectural journals and premium interior design editorial. It prioritizes "Handwerkskunst" (craftsmanship) and "Vertrauen" (trust) through a minimalist, structured approach that balances warmth with uncompromising professionalism.

The visual style leans heavily into **Minimalism** with an emphasis on negative space and precision. It utilizes a sophisticated typographic hierarchy and a restrained palette to allow high-quality photography of finished spaces to take center stage. The interaction model is quiet and deliberate, favoring subtle transitions over aggressive animations to evoke a sense of calm and luxury.

## Colors

The color palette is designed to feel organic and architectural. 

- **Warm Cream (#F5F0E8)** serves as the primary canvas, replacing stark whites to provide a tactile, paper-like quality. 
- **Deep Charcoal (#1E1E1E)** is used for high-contrast sections, such as footers or impact statements, providing a grounding architectural weight.
- **Rich Terracotta (#C1440E)** is the signature accent, used sparingly for calls-to-action and highlights to represent the warmth of fired clay and professional artistry.
- **Text (#1A1A1A)** ensures maximum legibility while maintaining a softer edge than pure black.

## Typography

This design system employs a classic pairing that echoes editorial excellence. 

**Noto Serif** is used for all headings. Its elegant serifs and high contrast convey tradition and premium quality. Large display sizes should use tighter letter spacing for a "masthead" appearance.

**Manrope** provides a clean, geometric contrast for body copy and functional UI. It ensures that technical details and descriptions remain highly readable and modern. All labels and overlines should utilize uppercase Manrope with increased letter spacing to reinforce the organized, professional nature of the service.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy, centered within the viewport to mimic the margins of a printed magazine. A 12-column grid provides the framework, but content is often offset or pushed to a 10-column width to create "breathing room" (Luftigkeit).

Vertical rhythm is expansive. Sections are separated by generous padding (120px+) to ensure every project or service feels significant. Thin 1px dividers in a low-opacity charcoal should be used to separate disparate content types without cluttering the visual field.

## Elevation & Depth

To maintain the editorial aesthetic, this design system avoids heavy shadows. Depth is communicated through **Tonal Layers** and **Low-Contrast Outlines**.

- **Cards:** Use a pure white background with a subtle 1px border (#1E1E1E at 10% opacity) rather than a shadow.
- **Hover States:** Elements should lift via a slight vertical offset (4px) and a change in background color or border intensity, accompanied by a smooth 300ms ease-in-out transition.
- **Overlays:** Use a subtle backdrop blur on navigation bars and modals to maintain context without sacrificing the clean, airy feel.

## Shapes

The shape language is **Sharp (0)**. Square corners reinforce the architectural precision of professional painting and renovation. This lack of rounding communicates a sense of structure, heritage, and "German engineering" quality.

Dividers and borders must be thin (1px) and consistent. Imagery should always be rectangular, avoiding circles or organic masks, to maintain the grid-based editorial integrity.

## Components

### Buttons
Primary buttons use the Rich Terracotta background with White text. They are sharp-edged, uppercase, and utilize an animated underline or a slight background color shift on hover. Secondary buttons use a Deep Charcoal outline with no fill.

### Cards
Service and Project cards are white blocks with sharp corners. They should feature large imagery followed by a Noto Serif headline. On hover, the image should scale slightly (1.05x) within its frame to create a window-like effect.

### Input Fields
Inputs are minimalist: a single 1px bottom border in Deep Charcoal. Labels appear above the line in small, uppercase Manrope. Focus states transition the border color to Terracotta.

### Thin Dividers
Used to structure long-form content. Dividers should never span the full container width; they should align with the grid columns to create an asymmetrical, modern look.

### Portfolio Gallery
A mix of 2-column and 3-column layouts with varying image aspect ratios to simulate a magazine spread. Captions use Body-md in an italicized variant of Noto Serif for a curated feel.