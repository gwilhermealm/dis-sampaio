---
name: Industrial Excellence System
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf4'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dde9ff'
  surface-container-highest: '#d5e3fd'
  on-surface: '#0d1c2f'
  on-surface-variant: '#43474f'
  inverse-surface: '#233144'
  inverse-on-surface: '#ebf1ff'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#1d1f1f'
  on-tertiary: '#ffffff'
  tertiary-container: '#323434'
  on-tertiary-container: '#9b9c9c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#f8f9ff'
  on-background: '#0d1c2f'
  surface-variant: '#d5e3fd'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 40px
  margin-mobile: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered for the construction logistics and materials distribution sector, where reliability, scale, and efficiency are paramount. The visual narrative balances the "heavy-duty" nature of the industry with a premium, corporate digital experience.

The core style is **Corporate / Modern**, leaning heavily into high-utility systematic layouts. It utilizes a structured hierarchy to convey institutional stability. Whitespace is used strategically to prevent data-heavy interfaces from becoming overwhelming, ensuring that project managers and procurement officers can navigate complex catalogs and logistics schedules with ease. The aesthetic is clean and high-contrast, utilizing "Safe" visual cues to foster trust and long-term professional partnerships.

## Colors

The color palette is anchored by a deep navy blue, representing the structural integrity and heritage of the construction industry. This is complemented by a light gray foundation that provides a modern, airy feel.

- **Primary (#003366):** Used for navigation bars, primary headings, and structural elements to anchor the UI.
- **Secondary/Accent (#FF8C00):** A high-visibility "Safety Orange" reserved strictly for Call-to-Action (CTA) elements, status indicators, and critical highlights.
- **Neutral/Surface (#F5F5F5):** Used for section backgrounds and card grouping to provide subtle contrast against the white base.
- **Functional Grays:** A range of slate-toned neutrals for body text, borders, and disabled states to ensure maximum legibility and accessibility.

## Typography

This design system employs a dual-font strategy to maximize both authority and readability. **Inter** is used for headlines and UI labels, providing a precise, systematic feel that aligns with industrial standards. **Source Sans 3** is utilized for body text, chosen for its exceptional legibility in long-form content and technical specifications.

Text scaling follows a clear hierarchy. Large display type is reserved for marketing hero sections, while UI headlines focus on clarity. Line heights are kept generous (1.5x - 1.6x) for body text to reduce eye strain during intensive procurement tasks.

## Layout & Spacing

The layout is built on a **12-column fluid grid** for desktop and tablet, transitioning to a single-column stack for mobile. A strict 8px base unit (the "unit") governs all padding and margins to ensure mathematical consistency.

- **Desktop:** 12 columns | 24px gutter | 40px minimum side margins.
- **Mobile:** 4 columns | 16px gutter | 16px side margins.

Content is grouped into logical modules using "stack" units. High-density information (like SKU lists) uses `stack-sm`, while distinct page sections use `stack-lg` to provide breathing room and visual distinction.

## Elevation & Depth

Visual hierarchy is achieved through a combination of **tonal layers** and **ambient shadows**. 

- **Level 0 (Flat):** Page background in white or light gray.
- **Level 1 (Low):** Cards and container surfaces use a subtle 1px border (#E2E8F0) and a soft, diffused shadow (0px 4px 12px rgba(0, 51, 102, 0.05)).
- **Level 2 (Hover/Active):** Elements lift slightly on interaction, increasing shadow opacity and blur (0px 8px 24px rgba(0, 51, 102, 0.1)).
- **Level 3 (Overlay):** Modals and dropdowns use a high-contrast shadow to separate from the main interface.

Shadows are tinted with the primary navy color rather than pure black to maintain a cohesive, premium brand feel.

## Shapes

The design system utilizes a **Rounded (8px)** corner language. This radius is applied consistently across all primary UI components—buttons, input fields, and cards—to soften the industrial aesthetic without appearing overly playful.

- **Small elements (Checkboxes):** 4px radius.
- **Standard elements (Buttons/Inputs):** 8px radius.
- **Large elements (Cards/Containers):** 16px (rounded-lg) or 24px (rounded-xl) to emphasize enclosure.

## Components

### Buttons
- **Primary:** Solid #FF8C00 with white text. High-contrast, bold, 8px radius.
- **Secondary:** Solid #003366 with white text for structural actions.
- **Tertiary:** Ghost style with #003366 border and text for less critical actions.

### Cards
Cards are the primary vehicle for product and logistics information. They feature a white background, Level 1 elevation, and 16px internal padding. Product cards should include a clear image area, title in Headline-md, and price/status in high-contrast Primary Navy.

### Navigation
The Top Navigation bar uses the Primary Navy (#003366) background to establish the brand immediately. Links are white with a 70% opacity for inactive states, transitioning to 100% with a Secondary Orange underline on hover.

### Input Fields
Inputs use a light gray background (#F8FAFC) with a subtle 1px border. On focus, the border transitions to Primary Navy with a 2px outer glow in the same color (at 10% opacity). Labels are positioned above the field using the Label-sm typography style.

### Data Tables
Given the nature of distribution, tables must be clean. Use "Zebra-striping" with #F5F5F5 on alternate rows. Headers should be sticky, using Primary Navy background and white text for maximum clarity during scrolling.