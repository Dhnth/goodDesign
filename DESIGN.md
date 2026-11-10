---
name: MotoRent Platform
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3d4a42'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6d7a72'
  outline-variant: '#bccac0'
  surface-tint: '#006c4a'
  primary: '#006948'
  on-primary: '#ffffff'
  primary-container: '#00855d'
  on-primary-container: '#f5fff7'
  inverse-primary: '#68dba9'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#9b3e3b'
  on-tertiary: '#ffffff'
  tertiary-container: '#ba5551'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#85f8c4'
  primary-fixed-dim: '#68dba9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005137'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ae'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#7f2928'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 3rem
    fontWeight: '700'
    lineHeight: 3.5rem
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: 0.875rem
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-trust, frictionless rental experience engineered for motorcycle enthusiasts, urban commuters, and weekend adventurers. It balances the precision of an automotive cockpit with the clarity and ease of modern hospitality booking.

The visual direction follows a **Modern Clean & Technical Minimalist** style. It leverages luminous white environments, surgical slate typography, and vibrant emerald accents to evoke reliability, mechanical health, and forward motion. The interface deliberately avoids heavy textures, prioritizing crisp content separation, scannable fleet metrics, and tactile interactive surfaces.

## Colors

The palette relies on high-contrast, functional hierarchy built for daylight legibility and rapid decision-making:

- **Primary (`#059669` / `#10B981`):** Represents vehicle availability, confirmed reservations, and principal conversions. Used for primary booking triggers, key verification states, and pricing highlights.
- **Secondary (`#0284C7`):** Represents navigation, ongoing active rentals, telematics metrics, and secondary feature highlights.
- **Neutral Palette (`#0F172A`, `#334155`, `#64748B`):** Deep slate tones provide structure. Body text anchors into `#334155`, headlines use `#0F172A`, and secondary metadata rests at `#64748B`.
- **Canvas & Surface System:**
  - Base background: Pure White (`#FFFFFF`).
  - Secondary surface container: Slate Tint (`#F8FAFC`).
  - Active track / border surface: Soft Slate (`#F1F5F9`).
- **Semantic Status Spectrum:**
  - **Available / Completed:** Emerald (`#059669` text on `#ECFDF5` background).
  - **Pending / In-Review:** Amber (`#D97706` text on `#FEF3C7` background).
  - **Rented / Active On-Trip:** Sky Blue (`#0284C7` text on `#E0F2FE` background).
  - **Maintenance / Overdue:** Rose (`#E11D48` text on `#FFE4E6` background).

## Typography

The typography uses Inter across all levels to maintain high legibility under dense vehicle specification cards and map overlay conditions.

- Numerical specs (displacement in cc, horsepower, daily rates) must use tabular lining figures (`font-variant-numeric: tabular-nums`) to align cleanly across fleet comparison matrices.
- Uppercase transformations are reserved strictly for technical abbreviations (e.g., ABS, TCS, DOHC) and `label-sm` category chips.
- Tight negative tracking is applied to display headlines to give motorcycle model designations an engineered, contemporary weight.

## Layout & Spacing

The layout is built on a responsive 12-column grid with a fluid maximum width of `1280px` for inventory discovery, expanding to `1440px` on dashboard map views.

- **Desktop (1024px+):** 12 columns, `1.5rem` (`24px`) gutters, `2rem` (`32px`) outer page margins. Map view uses a persistent 400px side rail with fluid canvas positioning.
- **Tablet (768px - 1023px):** 8 columns, `1rem` (`16px`) gutters, `1.5rem` (`24px`) margins. Vehicle comparison drawers switch to bottom sheet mode.
- **Mobile (< 768px):** 4 columns, `1rem` (`16px`) gutters, `1rem` (`16px`) margins. Filter bars collapse into horizontal sliding pills with a sticky bottom booking bar.
- Spacing rhythm adheres to an 8pt baseline scale. Gaps between related metadata (e.g., fuel level and range) sit at `space-xs` (4px) to `space-sm` (8px), while layout group boundaries utilize `space-lg` (24px) to `space-xl` (32px).

## Elevation & Depth

Visual hierarchy uses diffuse ambient drop shadows paired with hair-thin borders (`1px solid #E2E8F0`) to maintain separation without heavy ornamentation:

- **Level 0 (Flat):** Used for base page backgrounds (`#FFFFFF`) and content wells (`#F8FAFC`).
- **Level 1 (Card Rest):** Soft, low-contrast lift: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`. Outlined with a 1px `#F1F5F9` boundary.
- **Level 2 (Interactive Hover & Dropdowns):** Subtle float effect: `box-shadow: 0 10px 15px -3px rgba(15, 23, 42, 0.06), 0 4px 6px -4px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals & Checkout Sheets):** Strong foreground lift: `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.
- Surfaces never use saturated dark shadows; shadow tones are always tinted with Slate Neutral (`#0F172A`).

## Shapes

The system uses a baseline radius scale of `rounded-lg` (`12px`) for all primary surfaces to balance modern warmth with structured mechanical precision.

- **Vehicle Cards & Panels:** Standardized at `12px` (`0.75rem` / `rounded-lg`).
- **Inner Embedded Containers (spec metric boxes, photo carousels):** Sized down to `8px` (`0.5rem`) to maintain proportional concentric nesting.
- **Buttons and Inputs:** Fixed at `8px` or `12px` according to size hierarchy.
- **Pills & Status Badges:** Fully circular (`rounded-full` / `9999px`) to immediately distinguish them from clickable action cards and input boxes.

## Components

### Buttons
- **Primary:** Solid Emerald `#059669`, white text, `12px` radius. Hover shifts to `#047857` with transition duration `150ms`. Active state scales to `0.98`. Focus-visible shows an outline of `2px solid #059669` offset by `2px`.
- **Secondary:** Ghost surface with `#F1F5F9` background, `#0F172A` text. Hover shifts to `#E2E8F0`.
- **Outline:** 1px border in `#CBD5E1`, transparent background, `#0F172A` text. Hover fills to `#F8FAFC`.
- **Danger (Cancel Rental):** Rose soft background `#FFE4E6`, `#E11D48` text. Hover transitions to `#F43F5E` text.

### Chips & Status Badges
- Displayed with a pill profile (`rounded-full`), `space-xs` (4px) vertical padding, and `space-sm` (8px) horizontal padding.
- Text uses `label-md` weight.
- Includes a leading 6px circular dot indicator for instant status parsing:
  - *Available:* Emerald dot (`#10B981`) on `#ECFDF5` background.
  - *In-Review:* Amber dot (`#F59E0B`) on `#FEF3C7` background.
  - *On-Trip:* Sky blue dot (`#0284C7`) on `#E0F2FE` background.
  - *Maintenance:* Rose dot (`#E11D48`) on `#FFE4E6` background.

### Input Fields & Selectors
- **Container:** Minimum height 44px, white background, `1px solid #CBD5E1` border, `12px` radius.
- **State Changes:** On focus, border transitions to `#059669` with a subtle halo of `0 0 0 3px rgba(16, 185, 129, 0.15)`. Error states replace emerald with `#E11D48`.
- **Date-Range / Duration Pickers:** Styled as dual split-inputs with an inline arrow indicator and calendar icon (`#64748B`).

### Checkboxes & Radios
- Size: 18x18px. Radios use full rounding; checkboxes use a `4px` radius.
- Unchecked: `1.5px solid #94A3B8`.
- Checked: `#059669` fill with crisp white internal check or center dot.

### Motorcycle Fleet Cards
- Structural surface: Pure white background, `1px solid #F1F5F9` perimeter, `12px` radius.
- Aspect ratio for vehicle photo container: 16:10, sitting on `#F8FAFC` background with a subtle inner border bottom.
- Technical Spec Ribbon: A 3-column micro-grid directly under the title highlighting Engine CC, Transmission, and Seat Height using `body-sm` (`#64748B`).
- Footer: Bottom-aligned price lockup (`headline-sm` in `#0F172A` with `/day` in `#64748B`) aligned directly opposite the "Book Now" primary action.

### Telematics & Fuel Gauge Widget
- A custom progress pill tracking remaining rental duration, estimated mileage cap, and real-time fuel status using an Emerald-to-Ocean Blue gradient indicator over a `#F1F5F9` track.