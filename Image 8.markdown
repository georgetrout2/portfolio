---
name: Professional Tech Portfolio
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#43474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#455f87'
  primary: '#022448'
  on-primary: '#ffffff'
  primary-container: '#1e3a5f'
  on-primary-container: '#8aa4cf'
  inverse-primary: '#adc8f5'
  secondary: '#00668a'
  on-secondary: '#ffffff'
  secondary-container: '#40c2fd'
  on-secondary-container: '#004d6a'
  tertiary: '#1d2433'
  on-tertiary: '#ffffff'
  tertiary-container: '#323949'
  on-tertiary-container: '#9ca3b6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#adc8f5'
  on-primary-fixed: '#001c3b'
  on-primary-fixed-variant: '#2d486d'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#dce2f7'
  tertiary-fixed-dim: '#c0c6db'
  on-tertiary-fixed: '#141b2b'
  on-tertiary-fixed-variant: '#404758'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
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
  section-gap: 80px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system is built for a Computer Science professional, prioritizing clarity, technical precision, and a high-tech aesthetic. The brand personality is "The Modern Engineer"—reliable, methodical, and forward-thinking. The visual style leans into **Corporate/Modern** with a focus on systematic alignment and generous whitespace to reflect organized logic.

The emotional response should be one of immediate trust and competence. By balancing a deep navy primary with a vibrant, digital accent blue, the UI signals a bridge between traditional professional standards and cutting-edge software development.

## Colors

The palette is anchored by **Primary Navy (#1E3A5F)**, representing stability and academic rigor. **Accent Blue (#38BDF8)** is used sparingly for interactive elements, progress indicators, and highlights to inject energy into the "high-tech" look.

The background uses a cool, off-white **(#F8FAFC)** to reduce eye strain compared to pure white, while **Main Text (#111827)** provides maximum legibility. **Light Gray (#E5E7EB)** is reserved for structural elements like borders and dividers, maintaining a clean separation of content without adding visual noise.

## Typography

The typography system utilizes **Inter** for all primary communication due to its exceptional legibility and neutral, systematic character. To reinforce the Computer Science narrative, **JetBrains Mono** is introduced for labels, tags, and small technical metadata, providing a "code-adjacent" feel.

The hierarchy relies on tight letter spacing and heavy weights for large displays to create a modern, impactful presence. Body text maintains a comfortable 1.6 line height to ensure long-form project descriptions remain readable and professional.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop, centering content within a 1200px container to ensure a premium, curated feel. A 12-column system is used to organize project cards, with elements typically spanning 4 columns (for a 3-up grid) or 6 columns (for a 2-up grid).

Vertical rhythm is driven by an 8px base unit. Generous section gaps (80px+) are required to differentiate between the Hero, Projects, and Experience sections. On mobile, the grid collapses to a single column with 20px side margins, while padding within cards remains consistent to maintain the "high-tech" structural integrity.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layering**. Surfaces do not sit flat; they float slightly above the background to create a sense of sophistication.

- **Level 0 (Background):** #F8FAFC.
- **Level 1 (Cards/Nav):** Pure White (#FFFFFF) with a soft, diffused shadow (0px 4px 20px rgba(30, 58, 95, 0.08)).
- **Level 2 (Hover States/Modals):** Pure White (#FFFFFF) with a more pronounced shadow (0px 10px 30px rgba(30, 58, 95, 0.12)).

The navigation bar uses a subtle backdrop blur (12px) if transparency is applied, but primarily relies on a thin bottom border of #E5E7EB to define its fixed position.

## Shapes

The shape language is defined by **Rounded (Scale 2)** geometry. Standard UI components like input fields and small buttons use a 0.5rem (8px) radius. Larger containers, specifically project cards and hero image containers, use the `rounded-lg` (1rem / 16px) or `rounded-xl` (1.5rem / 24px) tokens to create a softer, more modern tech aesthetic.

This approach avoids the harshness of sharp corners while remaining more professional and "architectural" than fully pill-shaped components.

## Components

### Navigation Bar
A fixed top-bar using a height of 72px. It features the logo/name on the left and utility links on the right. Use a "blur" effect or a solid white background with a #E5E7EB bottom border.

### Buttons
- **Primary:** Navy (#1E3A5F) background with white text. High-contrast and bold.
- **Secondary:** Accent Blue (#38BDF8) with navy text for high visibility.
- **Ghost:** Transparent background with #E5E7EB border; navy text.

### Project Cards
The centerpiece of the portfolio. Cards must feature:
- A 16px corner radius.
- A subtle shadow that intensifies on hover.
- An image area with a 16:9 aspect ratio.
- A "Tech Stack" footer using `label-sm` chips with Light Gray backgrounds.

### Chips/Tags
Used for skills and languages. These should be rectangular with a 4px (Soft) radius, using a light tint of the Primary Navy (or Light Gray) and JetBrains Mono text.

### Hero Section
Center or left-aligned typography featuring the `display-lg` headline. Incorporate a subtle technical element, such as a faint grid pattern background or a high-quality abstract tech render, to ground the Computer Science theme.