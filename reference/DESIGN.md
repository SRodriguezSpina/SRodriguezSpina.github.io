---

name: Earthy Precision
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e4e2e0'
  on-surface: '#1b1c1a'
  on-surface-variant: '#55423d'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ee'
  outline: '#88726c'
  outline-variant: '#dcc1b9'
  surface-tint: '#9a4429'
  primary: '#9a4429'
  on-primary: '#ffffff'
  primary-container: '#db7657'
  on-primary-container: '#551300'
  inverse-primary: '#ffb59f'
  secondary: '#7f5443'
  on-secondary: '#ffffff'
  secondary-container: '#ffc5af'
  on-secondary-container: '#7a4f3e'
  tertiary: '#7e5441'
  on-tertiary: '#ffffff'
  tertiary-container: '#b88771'
  on-tertiary-container: '#432213'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59f'
  on-primary-fixed: '#3a0a00'
  on-primary-fixed-variant: '#7c2e15'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#f3baa4'
  on-secondary-fixed: '#311306'
  on-secondary-fixed-variant: '#643d2d'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#f1baa3'
  on-tertiary-fixed: '#301305'
  on-tertiary-fixed-variant: '#643d2c'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2e0'
  surface-canvas: '#F3EBDB'
  text-primary: '#4A3F38'
  border-subtle: '#ACACAB'
  border-medium: '#A4A4A4'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-xs:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem

##   space-xl: 2.5rem



## Brand & Style

This design system combines technical rigor, architectural clarity, and utilitarian restraint with an organic, tactile sensibility. Designed for high-density documentation, technical portfolios, and analytical tools, the interface balances precision engineering with human warmth. 

The aesthetic synthesizes functional minimalism and parchment-like warmth. It replaces clinical, icy digital tech surfaces with an earthy, tactile substrate—evoking archival field notes, physical schematics, and natural stone. The experience must feel deliberate, unhurried, and deeply scannable: information-dense, impeccably organized, and free from superficial decoration.

## Colors

The palette is anchored in an earthy, warm neutral schema configured for high daylight legibility and tactile calm.

- **Primary Canvas (**`#F3EBDB`**)**: Warm parchment tone serving as the default application substrate. Softens harsh contrast while maintaining distinct separation from high-density data.
- **High-Contrast Foreground (**`#4A3F38`**)**: Deep roast espresso utilized for all headlines, core prose, dominant metrics, and high-priority UI elements.
- **Primary Action Accent (**`#DB7657`**)**: Rich terracotta / burnt sienna applied exclusively to interactive calls to action, focused states, and essential status accents.
- **Secondary Structural Accents (**`#926452`**,** `#DDA891`**)**: Warm chestnut brown (`#926452`) supports metadata grouping and secondary buttons, while warm clay peach (`#DDA891`) defines recessed indicator fills, selection pills, and badge surfaces.
- **Architectural Grays (**`#747472`**,** `#A4A4A4`**,** `#ACACAB`**)**: Subdued structural neutrals dedicated to hairline grids, divider rules, passive borders, and secondary data labels.



## Typography

Typography balances sharp technological execution with warm optical comfort.

- **Geist** handles natural language headings and running narrative body copy. Tight letter spacing on headlines creates an authoritative, modern feel, while generous line heights across body tiers preserve comfort against the parchment background.
- **JetBrains Mono** is reserved exclusively for tabular data, code expressions, telemetry metrics, timestamps, status indicators, and technical metadata.
- All technical taxonomy tags, metadata chips, and system status markers must strictly implement the `label-*` tiers.



## Elevation & Depth

Visual hierarchy relies strictly on **tonal layers** and **low-contrast architectural outlines**. Diffuse blur shadows and dramatic drops are avoided entirely to maintain a clean, documentarian aesthetic.

- **Canvas Foundation**: `#F3EBDB` provides the grounding field.
- **Card and Panel Elevation**: Elevated surfaces adopt lightened warm-parchment tinting (`rgba(255, 255, 255, 0.65)` layered over `#F3EBDB`) outlined with a structural hairline border (`1px solid #ACACAB`).
- **Recessed Areas & Code Insets**: Technical outputs and code blocks sink slightly into the canvas using a darkened warm neutral undertone (`rgba(74, 63, 56, 0.05)`) bounded by `1px solid #A4A4A4`.
- **Interactive State Elevation**: Hover and focus transitions replace drop shadows with outline contrast shifting from `#ACACAB` to `#747472`, accompanied by subtle background shift.



## Shapes

The design system maintains a compact, disciplined geometry using a soft roundedness level (`1`):

- Standard elements (inputs, buttons, badges) utilize `0.25rem` (`4px`) corner radii.
- Structural cards, code containers, and dialog panels employ `rounded-lg` (`0.5rem` / `8px`).
- Circular and pill formats are prohibited for content surfaces, preserving a crisp, architectural framing across all content blocks.



## Components



### Buttons

- **Primary**: Background `#DB7657`, text `#F3EBDB`, border `1px solid #DB7657`. Hover: `#926452`. Focus ring: `2px solid #DB7657` with `2px` offset on `#F3EBDB`.
- **Secondary**: Background transparent, text `#4A3F38`, border `1px solid #A4A4A4`. Hover: background `rgba(74, 63, 56, 0.06)`, border `#747472`.
- **Tertiary / Link**: Background transparent, text `#DB7657` with JetBrains Mono inline brackets (`[action]`).



### Chips & Badges

- **Technical Chip**: JetBrains Mono `label-xs`, padding `0.25rem 0.5rem`, background `rgba(74, 63, 56, 0.06)`, border `1px solid #ACACAB`, text `#4A3F38`.
- **Accent Badge**: Background `rgba(219, 118, 87, 0.12)`, text `#926452`, border `1px solid #DDA891`.



### Lists & Technical Tables

- **Key-Value Pairs**: Flex or CSS grid row. Key term (`<dt>`) styled in `label-sm` with `#747472`; value (`<dd>`) styled in `body-sm` with `#4A3F38`. Rows are separated by a hairline rule (`1px solid #ACACAB`).
- **Log / Data Lists**: Monospace terminal format with alternating micro-shaded row bands (`rgba(74, 63, 56, 0.03)`).



### Inputs & Controls

- **Text Inputs**: Background `rgba(255, 255, 255, 0.5)`, text `#4A3F38`, border `1px solid #A4A4A4`, rounded `0.25rem`. Active/Focus: border `#DB7657` without ambient glow.
- **Checkboxes & Radios**: `16px` squared inputs with `1px solid #A4A4A4`. Active fill in `#DB7657` featuring check mark in `#F3EBDB`.



### Cards & Panels

- **Structure**: Lightened parchment overlay background, `1px solid #ACACAB` border, and `space-md` internal padding.
- **Panel Header**: Features title in Geist `headline-sm` alongside metadata or git commit IDs in JetBrains Mono `label-xs` tinted to `#747472`.

