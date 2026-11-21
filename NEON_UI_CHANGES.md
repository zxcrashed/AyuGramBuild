# AyuGram Neon UI source changes

This source patch changes the desktop client itself, not only an importable theme.

## Implemented in source

- Main window defaults are larger and the left/main/third-column width constraints are tuned for a wider, three-column desktop layout.
- Chat rows have more vertical space and larger avatars, with updated name/preview positions.
- The active/selected chat row is painted as an inset rounded surface instead of a full-width rectangular highlight.
- Tagged and forum row heights were adjusted to remain consistent with the new default row geometry.

## Reference direction

The supplied video shows a dark, near-black Telegram window with rounded surfaces and green accents. The rounded row treatment is implemented in the painter. The palette still follows the active AyuGram theme; apply a dark green-accent theme for the closest color match.

## Build status

This is a source-level UI patch. No Windows executable was built or tested in this environment. Build using the project's Windows build instructions and its required Qt/dependency toolchain.
- Message bubble corner radii are increased to create a softer, more modern chat surface.
