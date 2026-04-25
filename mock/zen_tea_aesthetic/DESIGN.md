---
name: Zen Tea Aesthetic
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#3d6930'
  on-secondary: '#ffffff'
  secondary-container: '#bdf1a8'
  on-secondary-container: '#426f35'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1c1c'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#bdf1a8'
  secondary-fixed-dim: '#a2d48f'
  on-secondary-fixed: '#022100'
  on-secondary-fixed-variant: '#25501a'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  h1:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '400'
    lineHeight: '1.3'
  h3:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
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
    lineHeight: '1.2'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  section-padding: 120px
  element-gap: 16px
---

## Brand & Style

The design system is anchored in the Japanese concept of *Ma*—the pure, intentional void that gives meaning to the objects within it. This design system targets a discerning audience that values ritual, quality, and tranquility. The brand personality is quiet yet confident, blending centuries of tea tradition with a modern, editorial edge.

The chosen style is **Minimalism** with a focus on high-end retail. By utilizing generous whitespace and a strictly controlled color palette, the UI recedes to let the vibrant textures of the tea leaves and the craftsmanship of the ceramics take center stage. The emotional response is one of immediate calm and clarity, mirroring the experience of a tea ceremony.

## Colors

The palette is intentionally restrained to evoke sophistication. The base is a pure, gallery-white to maximize light and space. 

- **Primary:** A deep, ink-like black used for typography and structural elements to provide a grounded, authoritative feel.
- **Accent:** A vibrant, natural matcha green, pulled directly from high-grade tea liquor. This color is used sparingly for call-to-actions, notifications, or subtle highlights to draw the eye without breaking the "Zen" atmosphere.
- **Neutrals:** A range of soft grays facilitate hierarchy and separation without the harshness of high-contrast lines.

## Typography

This design system employs a sophisticated typographic pairing to bridge the gap between heritage and contemporary lifestyle. 

**Noto Serif** is used for all major headings. Its elegant, high-contrast strokes evoke the precision of Japanese calligraphy and the premium nature of the product. **Manrope** serves as the functional workhorse for body copy and UI labels; its geometric yet refined construction ensures maximum readability on screens while maintaining a modern, neutral tone. Note the use of increased letter spacing for labels to enhance the spacious, high-end feel.

## Layout & Spacing

The layout follows a **Fixed Grid** model to ensure a curated, editorial experience that feels stable and intentional. Content is centered within a generous max-width container, surrounded by significant "safe zones."

The spacing rhythm is aggressive in its use of white space. Section vertical padding is intentionally large (120px+) to force the user to slow down and appreciate each content block. Gutters are kept wide to prevent the UI from feeling cluttered, even on smaller desktop screens.

## Elevation & Depth

To maintain a flat, Zen-like aesthetic, this design system avoids traditional shadows and heavy 3D effects. Depth is conveyed through **Tonal Layers** and **Low-Contrast Outlines**.

- Surfaces are mostly flat white.
- Hover states use subtle shifts in background color (e.g., White to #F9F9F9) or hair-line borders (1px) in light gray.
- If a pop-over or modal is required, use a very soft, diffused ambient shadow with 0% offset and a large blur radius to simulate a gentle lift rather than a harsh projection.

## Shapes

The design system utilizes **Sharp (0px)** edges for all primary UI components, including buttons, input fields, and product cards. This architectural approach mirrors the clean lines of Japanese tea houses and traditional packaging. The lack of rounded corners communicates precision, luxury, and a "straight-edged" modernism.

## Components

### Buttons
Primary buttons are solid Black with White text. Hover effects are subtle—typically a transition to the accent Green or a slight reduction in opacity. Secondary buttons use a 1px Black outline with a transparent background. All buttons use the "Label-sm" typography style for a refined, precise look.

### Product Cards
Cards are borderless and rely on high-quality photography against the white background. Information is center-aligned below the image using Noto Serif for the product name and Manrope for the price.

### Input Fields
Inputs are defined by a simple 1px bottom border (border-bottom) rather than a full box, minimizing visual noise in forms.

### Chips & Tags
Used for tea types (e.g., "Ceremonial Grade"). These are small, text-only elements or have a very light gray background with sharp corners, ensuring they do not distract from the primary product imagery.

### Navigation
The header should be spacious with a transparent or pure white background. Links should use the "Label-sm" style with a subtle underline appearing on hover.