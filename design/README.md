# Orders page redesign concepts

These mockups are concept images for improving the account orders screen shown in the user's screenshot.

Files:

- `orders-redesign-desktop.svg` - Desktop account/orders redesign
- `orders-redesign-mobile.svg` - Mobile adaptation of the same design system

## Design goals

1. Replace the dense table feel with spacious order cards.
2. Make status easier to scan with color-coded pills and progress indicators.
3. Elevate the account sidebar using a profile hero and stronger active-state styling.
4. Promote key actions like Track, Invoice, Reorder, and Support.
5. Improve visual hierarchy with summary stats, softer surfaces, and modern spacing.

## Recommended UI changes for implementation

- Use a soft app background with one large white content surface.
- Keep the left account menu, but make the active row a rounded highlighted card.
- Add a top summary area with order metrics or customer shortcuts.
- Convert each order row into a card with:
  - store thumbnail or brand mark
  - order title and metadata
  - status pills
  - amount
  - prominent primary/secondary action buttons
  - optional shipping progress line for active orders
- Surface support/returns as a visible CTA instead of burying it in navigation.

## Suggested palette

- Primary navy: `#0F172A` or `#1D3557`
- Accent blue: `#2563EB` or `#4DA3FF`
- Accent teal: `#14B8A6`
- Success: `#16A34A`
- Warning: `#D97706`
- Surface: `#F8FAFC`
- Border: `#E2E8F0`
- Text muted: `#64748B`

## Suggested typography

- Headings: 600-700 weight
- Body: 400-500 weight
- Use tighter heading sizes and more breathing room between groups

## Notes

These are static SVG mockups because the current repository does not contain the source code for the actual orders page.
