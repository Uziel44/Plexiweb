---
name: Plexiweb Design System
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
  on-surface-variant: '#43474f'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#747780'
  outline-variant: '#c4c6d0'
  surface-tint: '#405f91'
  primary: '#001736'
  on-primary: '#ffffff'
  primary-container: '#002b5b'
  on-primary-container: '#7594ca'
  inverse-primary: '#a9c7ff'
  secondary: '#115cb9'
  on-secondary: '#ffffff'
  secondary-container: '#659dfe'
  on-secondary-container: '#003370'
  tertiary: '#07182b'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d2d41'
  on-tertiary-container: '#8495ad'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#a9c7ff'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#264778'
  secondary-fixed: '#d7e2ff'
  secondary-fixed-dim: '#acc7ff'
  on-secondary-fixed: '#001a40'
  on-secondary-fixed-variant: '#004491'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  surface-white: '#FFFFFF'
  deep-navy: '#001E3C'
  slate-border: '#E2E8F0'
  accent-blue: '#3B82F6'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 60px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 42px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
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
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 80px
  section-gap: 120px
  container-max: 1280px
---

## Brand & Style

The design system for this digital agency focuses on **Corporate Minimalism** with a high-tech edge. It is built to communicate precision, reliability, and engineering excellence. The aesthetic prioritizes clarity and functional beauty, ensuring that the agency's portfolio and services are presented without visual noise.

The style leverages:
- **Technological Precision**: Sharp layouts with purposeful alignment.
- **Architectural Depth**: Using light and shadow to create a sense of physical layering.
- **Intentional Breathing Room**: Extensive white space to reduce cognitive load and emphasize high-value content.
- **Human-Centric Interface**: While the aesthetic is "tech," the interaction model is soft and approachable through rounded geometry.

## Colors

The palette is anchored by **Deep Navy (#002B5B)**, representing the professional stability of an established development partner. 

- **Primary & Secondary**: Used for brand identity, primary actions, and navigational anchors.
- **Neutral Scale**: Uses cool-toned grays to maintain the "tech" feel. Avoid warm grays or beiges.
- **Backgrounds**: The system defaults to a light mode. Use `surface-white` for primary content containers and `neutral_color_hex` (F8FAFC) for page backgrounds to provide subtle contrast between sections.
- **Accents**: Use `accent-blue` sparingly for interactive states like hover effects or success indicators.

## Typography

The system utilizes **Inter** exclusively to achieve a systematic, utilitarian look that remains highly legible across all resolutions.

- **Scale**: A strict typographic scale ensures hierarchy. Display sizes use tighter letter spacing and heavier weights to feel "engineered."
- **Body Text**: Maintain a generous line height (1.5x or more) to support readability in long-form technical descriptions.
- **Labels**: Use medium or semi-bold weights for small labels (UI metadata, tags) to ensure they don't disappear against the white space.
- **Color**: Use Deep Navy for headings and Tertiary Slate for body text to create secondary visual hierarchy through color rather than just size.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid** model. Content is contained within a max-width of 1280px on desktop but scales fluidly on smaller viewports.

- **Grid**: A 12-column grid is used for desktop, 8 for tablet, and 4 for mobile. 
- **Section Spacing**: Large vertical gaps (`section-gap`) are used between major content blocks to prevent the interface from feeling cluttered.
- **Rhythm**: All spacing (padding, margins) must be a multiple of the 4px base unit. 
- **Alignment**: Align all text-based components to the left to maintain a clean, professional vertical axis. Avoid centered body text.

## Elevation & Depth

This design system uses **Tonal Layering** combined with **Ambient Shadows** to define hierarchy.

- **Level 0 (Base)**: The background (`#F8FAFC`).
- **Level 1 (Cards/Surfaces)**: White surfaces (`#FFFFFF`) with a very soft, diffused shadow (0px 4px 20px rgba(0, 43, 91, 0.05)).
- **Level 2 (Interaction/Floating)**: Elements like dropdowns or active modals use a more pronounced shadow with a slight blue tint (0px 12px 32px rgba(0, 43, 91, 0.12)).
- **Outlines**: For low-elevation elements like input fields, use a 1px solid border (`#E2E8F0`) instead of shadows to maintain a "clean tech" look.

## Shapes

The shape language is **Rounded**, balancing the professional navy tones with a sense of modern approachability.

- **Core Elements**: Buttons, inputs, and cards use a 0.5rem (8px) radius.
- **Large Containers**: Section wrappers or feature cards may use `rounded-xl` (1.5rem/24px) to create a softer, more premium aesthetic.
- **Icons**: Icons should be housed in circular or softly rounded containers to contrast with the rigid grid.

## Components

### Buttons
- **Primary**: Solid Deep Navy background, white text, 8px radius. On hover, transition to Secondary Blue.
- **Secondary**: Transparent background with a 1px Navy border. Use for less critical actions.
- **Tertiary/Ghost**: Text-only with a subtle background color change on hover.

### Input Fields
- White background, 1px Slate border, 8px radius. 
- Active state: 2px Deep Navy border with a 4px soft blue outer glow.

### Cards
- White background, 8px-12px radius, Level 1 shadow. 
- Internal padding should be generous (24px or 32px) to maintain the minimalist feel.

### Chips & Tags
- Used for technology stacks (e.g., "React", "Node.js"). 
- Light gray background, Navy text, 100px (Pill) radius, small label typography.

### Lists
- Use custom bullet points (small blue squares or checkmarks) rather than standard browser dots to reinforce the "development" theme.