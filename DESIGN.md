---
name: Aura & Slate
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
  on-surface-variant: '#45474a'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#76777b'
  outline-variant: '#c6c6ca'
  surface-tint: '#5d5e62'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1a1c1f'
  on-primary-container: '#838487'
  inverse-primary: '#c6c6ca'
  secondary: '#715b3b'
  on-secondary: '#ffffff'
  secondary-container: '#fddeb5'
  on-secondary-container: '#786140'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#0e1b34'
  on-tertiary-container: '#7884a2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e6'
  primary-fixed-dim: '#c6c6ca'
  on-primary-fixed: '#1a1c1f'
  on-primary-fixed-variant: '#45474a'
  secondary-fixed: '#fddeb5'
  secondary-fixed-dim: '#e0c29b'
  on-secondary-fixed: '#281802'
  on-secondary-fixed-variant: '#584325'
  tertiary-fixed: '#d9e2ff'
  tertiary-fixed-dim: '#bac6e7'
  on-tertiary-fixed: '#0e1b34'
  on-tertiary-fixed-variant: '#3b4662'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
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
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-tablet: 32px
  margin-mobile: 20px
---

## Brand & Style

The brand identity centers on the intersection of architectural permanence and digital fluidity. It targets high-net-worth property owners and discerning travelers who value discretion, precision, and effortless luxury. The emotional response should be one of immediate calm and absolute confidence in the platform's competence.

The design system adopts a **Modern-Minimalist** style with **Luxurious Tactility**. It prioritizes expansive whitespace to allow high-fidelity architectural photography to breathe, utilizing "quiet" UI elements that recede until needed. The aesthetic is punctuated by high-contrast typography and subtle, layered depth to evoke the feeling of a premium physical concierge service.

## Colors

The palette is anchored by **Deep Charcoal** (#121417), providing a weighted, authoritative foundation. **Brushed Gold** (#BFA37E) is used exclusively as a sophisticated accent for primary actions, success states, or premium tier indicators, signifying value and high-touch service. 

**Deep Royal Blue** (#1E2A44) serves as a secondary functional color for interactive elements like links and active navigation states. The background strategy utilizes **Crisp White** (#FFFFFF) for primary surfaces and a very light **Neutral Gray** (#F9F9F9) for secondary layout containers to create subtle contrast without introducing visual noise.

## Typography

This design system employs a high-contrast typographic pairing to balance heritage with technology. **Libre Caslon Text** is utilized for headlines and display text, conveying the established authority of a high-end estate. Its classic proportions provide an editorial feel to property descriptions and brand storytelling.

**Manrope** is the workhorse for all functional UI, data, and body copy. Chosen for its modern, geometric structure and exceptional legibility at small sizes, it ensures the platform feels "tech-forward" and efficient. Labels use a semi-bold weight with increased letter spacing and uppercase styling to provide clear hierarchy in dense management interfaces.

## Layout & Spacing

The layout follows a **Fixed-Width Grid** on desktop to maintain the integrity of professional photography compositions, transitioning to a **Fluid Grid** on mobile devices. A 12-column system is used for desktop, while mobile scales down to a 4-column structure.

The spacing rhythm is based on an 8px base unit. Generous external margins (64px on desktop) create a "gallery" effect, framing the content. Internal padding within cards and containers should favor the larger end of the scale (e.g., 32px or 40px) to reinforce the premium, uncrowded aesthetic.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layering**. Shadows are extremely soft, utilizing large blur radii (20px+) with low-opacity (5-8%) charcoal tints to mimic natural, diffuse light. 

Primary surfaces are pure white, while the background is a subtle off-white, creating a natural lift for content cards. Interactive elements use a slightly more pronounced "active" shadow on hover to simulate the element physically rising toward the user. No harsh borders are used; depth is created entirely through light and shadow.

## Shapes

The shape language is defined by **Medium Roundedness**. A corner radius of 8px (0.5rem) is the standard for cards and buttons, providing a modern, approachable feel that softens the high-contrast color palette. 

Large property containers and hero images utilize 16px (1rem) radii to feel like distinct, high-end objects within the UI. Form inputs and smaller interactive components strictly follow the 8px standard to maintain a crisp, professional appearance.

## Components

### Buttons
Primary buttons utilize the Deep Charcoal background with White text for maximum authority. The "Brushed Gold" accent is reserved for "Book Now" or "Featured" actions. Buttons feature a subtle 1px inset border in a lighter shade of the background color to provide a "milled" look.

### Input Fields
Inputs are minimal, featuring a 1px bottom border in a light gray (#E0E0E0). Upon focus, the border transitions to Deep Charcoal. Labels always remain visible, floating above the input in the `label-sm` style.

### Cards
Property cards are the core component. They must feature a 3:2 aspect ratio for imagery, 16px rounded corners, and no visible border. Content is padded by 24px, with the price point set in the `headline-md` serif font to emphasize value.

### Chips & Tags
Used for property amenities (e.g., "Pool," "Concierge"). These use a light neutral fill (#F0F0F0) and the `label-sm` Manrope font. They are pill-shaped (100px radius) to contrast against the more structured 8px radius of larger containers.

### Date Pickers & Search
These components should feel like a premium stationary set—clean lines, high-contrast text, and a focused interface that hides secondary options until interaction occurs.