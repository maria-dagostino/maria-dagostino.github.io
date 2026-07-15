---
name: Analytical Creative
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
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#110200'
  on-tertiary: '#ffffff'
  tertiary-container: '#391303'
  on-tertiary-container: '#b5785f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#fdb69a'
  on-tertiary-fixed: '#351002'
  on-tertiary-fixed-variant: '#6b3a25'
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
  headline-md:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
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
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1200px
  section-gap: 120px
  stack-gap: 32px
  grid-gutter: 24px
  margin-mobile: 20px
  margin-desktop: 60px
---

## Brand & Style

The design system is built for a professional narrative that merges the precision of data science with the intentionality of creative design. The brand personality is **Sophisticated, Decisive, and Lucid**. It targets hiring managers in tech and creative industries who value both technical rigor and aesthetic clarity.

The visual style is **High-End Minimalism**. It prioritizes extreme legibility, generous whitespace, and a strict structural hierarchy. By removing all non-essential decorative elements, the design system allows the data visualizations and project outcomes to remain the focal point. The emotional response should be one of immediate trust and intellectual calm.

## Colors

The palette is anchored by a high-contrast relationship between a "Crisp White" foundation and "Midnight Navy" accents. 

- **Primary (#001F3F):** Used for headlines, primary action buttons, and active states. It conveys authority and depth.
- **Secondary (#64748B):** A muted slate used for secondary labels, metadata, and iconography to ensure they don't compete with primary information.
- **Neutral/Background (#F8FAFC):** A very cool, clean white used for section backgrounds to reduce eye strain and maintain a modern feel.
- **Stroke/Border:** A ultra-thin light gray (#E2E8F0) is used for structural definition without adding visual weight.

## Typography

This design system utilizes **Inter** exclusively to achieve a systematic, "SaaS-like" aesthetic. The key is extreme weight contrast: bold, tight-tracked displays paired with airy, well-leaded body copy.

- **Headlines:** Use Bold (700) or SemiBold (600) weights with negative letter-spacing for a "compact" and impactful look.
- **Body:** Use Regular (400) weight in Slate Gray (#475569) to soften the reading experience against the white background.
- **Labels:** Use Medium (500) or SemiBold (600) with slight letter-spacing and uppercase styling for "Data Point" headers or small metadata tags.

## Layout & Spacing

The layout follows a **Strict 12-Column Fixed Grid** for desktop, ensuring data visualizations align perfectly with text blocks.

- **Desktop:** 1200px max-width container centered. Use 120px vertical padding between major sections to emphasize the minimalist "gallery" feel.
- **Tablet:** 8-column grid with 40px side margins.
- **Mobile:** Single column fluid layout with 20px side margins.
- **Rhythm:** All spacing (padding, margins, gaps) must be multiples of 8px to maintain mathematical harmony, reflecting the "data-driven" nature of the brand.

## Elevation & Depth

This design system avoids traditional heavy shadows in favor of **Tonal Layering and Sharp Outlines**.

- **Surfaces:** Most content sits flat on the primary background. 
- **Project Cards:** Use a 1px solid border (#E2E8F0). On hover, the border color shifts to the Primary Navy (#001F3F), and a very subtle, large-radius "Ambient Shadow" (0px 20px 40px rgba(0, 31, 63, 0.05)) is applied to suggest a gentle lift.
- **Interactive Elements:** Use "Ghost" states for secondary buttons—1px borders with no fill—to maintain a lightweight appearance.

## Shapes

The shape language is **Structured and Precise**. 

- **Corners:** A "Soft" (0.25rem/4px) radius is applied to buttons, input fields, and cards. This provides just enough approachability without losing the professional, architectural feel of sharp corners.
- **Interactive States:** Buttons and Chips maintain the same 4px radius. Avoid pill shapes (rounded-full) as they are too casual for this specific analytical narrative.

## Components

- **Project Cards:** The signature component. Feature a large image container with a subtle 1px border. The text area below should use `label-md` for categories and `headline-sm` for titles.
- **Primary Buttons:** Solid `#001F3F` fill with white text. High-contrast, rectangular but slightly softened corners.
- **Data Chips:** Small, light gray backgrounds (#F1F5F9) with `label-sm` text. Used for "Tools Used" (e.g., Python, SQL, Tableau).
- **Text Inputs:** Minimalist underline or 1px light border. Focus state should only change the border color to Primary Navy; avoid thick focus rings.
- **Data Visualizations:** Charts should use a refined palette derived from the Primary Navy, utilizing tints (60%, 40%, 20% opacity) to maintain a monochromatic, sophisticated look.
- **Navigation:** Simple text-based links in `label-md`. Active states are indicated by a 2px underline in Primary Navy rather than a background change.