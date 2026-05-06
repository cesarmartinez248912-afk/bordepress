---
name: Precision Industrial
colors:
  surface: '#f7fafd'
  surface-dim: '#d7dadd'
  surface-bright: '#f7fafd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f7'
  surface-container: '#ebeef1'
  surface-container-high: '#e5e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#181c1e'
  on-surface-variant: '#43474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f4'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#0e0300'
  on-tertiary: '#ffffff'
  tertiary-container: '#341600'
  on-tertiary-container: '#ce6c0a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#713700'
  background: '#f7fafd'
  on-background: '#181c1e'
  surface-variant: '#e0e3e6'
typography:
  h1:
    fontFamily: Work Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Work Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Work Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  button:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The brand personality of the design system is anchored in industrial reliability and corporate agility. It targets business owners and procurement managers who value efficiency, durability, and professional presentation. The UI evokes a sense of "measure twice, cut once" precision, reflecting the technical nature of embroidery and uniform manufacturing.

The design style follows a **Corporate / Modern** movement. It utilizes generous whitespace to signal premium quality and organization. High-resolution imagery of textured fabrics and precision machinery serves as a secondary visual layer, grounding the clean digital interface in the physical world of textiles. The interface is optimized for speed and clarity, ensuring that a professional audience can navigate large catalogs or service lists with minimal cognitive load.

## Colors

The palette is dominated by Deep Navy Blue, which establishes authority and trust. Pure White is used as the primary canvas to maintain a clean, clinical industrial feel. Vibrant Gold/Orange serves as the "action" color, reserved exclusively for conversion points and critical highlights to ensure high visibility against the dark primary tones.

A subtle neutral grey is utilized for background sections to break up long pages without sacrificing the minimalist aesthetic. Success and error states should avoid the brand orange to prevent semantic confusion; instead, use standard green and red utility tones at low saturation.

## Typography

This design system uses **Work Sans** for headings to provide a grounded, professional architectural feel. Its slightly wider stance suggests stability and industrial strength. For body copy and functional elements, **Inter** is used for its exceptional legibility and systematic, utilitarian appearance.

Hierarchy is maintained through significant size stepping and weight contrast. Headlines should use the primary Navy Blue, while body text uses a slightly softened near-black to improve long-form reading comfort. Labels and small captions use increased letter-spacing and uppercase styling to denote metadata or secondary information.

## Layout & Spacing

The layout utilizes a **Fixed Grid** system centered on the viewport. A standard 12-column grid is employed with a 1280px maximum container width to maintain a professional, structured corporate look on desktop displays. 

Spacing is based on an 8px modular scale. Generous vertical padding (the 'lg' and 'xl' units) is applied between sections to create a sense of breathability and high-end positioning. Component-level spacing follows a tighter rhythm to ensure that functional elements like forms and data tables feel compact and efficient.

## Elevation & Depth

To maintain the "agile" and modern feel, the design system avoids heavy, dark shadows. Instead, it employs **Tonal Layers** and **Low-contrast Outlines**. Surfaces are primarily separated by subtle 1px borders in a light grey-blue or by shifting background colors between Pure White and the neutral off-white.

When depth is required for interactive elements like cards or dropdowns, a "soft-focus" shadow is used: a very high blur radius (20px+) with very low opacity (5-8%) using a navy-tinted shadow color rather than pure black. This creates a sophisticated, atmospheric lift rather than a heavy physical one.

## Shapes

The shape language balances the rigid nature of industrial machinery with the approachability of modern service. A **Rounded (0.5rem)** base radius is applied to standard components like buttons and input fields. 

Larger containers, such as featured cards or image frames, utilize the `rounded-lg` (1rem) setting to soften the overall composition. This specific level of roundedness ensures the UI feels contemporary and friendly without losing the serious, "squared-away" character required for a corporate uniform supplier.

## Components

### Buttons
Primary buttons use the vibrant Gold/Orange (#FF8C00) with white text for maximum "Call to Action" impact. Secondary buttons use the Navy Blue (#001F3F) with a ghost (outlined) or solid style depending on the background contrast. All buttons feature rounded corners and a subtle scale-down effect on click to provide tactile feedback.

### Navigation
The navigation bar is **sticky**, utilizing a solid Navy Blue background with White links to remain persistent and authoritative as the user scrolls. A subtle bottom-border in Gold/Orange provides a high-contrast "line of precision" during scroll.

### Cards & Industrial Lists
Product cards for uniforms feature a subtle 1px border and no default shadow, gaining a soft shadow only on hover. Lists for industrial specs (e.g., fabric weight, stitch count) use high-contrast labels and Work Sans for numerical data to emphasize technical accuracy.

### Input Fields
Inputs are clean with a 1px Navy outline that thickens to 2px on focus. Labels are positioned above the field in the `label-sm` typography style to ensure clarity during the ordering or quote-request process.

### Professional Iconography
Icons should be thin-stroke, geometric, and monochromatic (using Navy or Orange for active states). They should represent "precision," "quality," and "logistics" (e.g., rulers, needles, trucks, and shields).