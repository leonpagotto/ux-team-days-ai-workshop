# Workshop Presentation Icons

This directory contains SVG icons used throughout the AI Workshop presentation.

## Icon Philosophy
- **Outline-only style** - No solid fills (except small dots like skill levels)
- **IKEA color palette** - #00853F (green), #0058A3 (blue), #E00751 (pink), #FBD914 (yellow), #F57C00 (orange), #6A1B9A (purple)
- **Consistent stroke-width** - Typically 2px for main icons, 2.5px for emphasis
- **Scalable** - 24x24 to 80x80px viewBox, scales via width/height attributes

## Current Icons (Inline SVG)
All icons are currently embedded inline in index.html for simplicity and performance.

## Future Enhancement
Icons could be externalized to separate .svg files and referenced via:
- `<img src="icons/star-outline.svg">` or
- `<svg><use href="icons.svg#star-outline"></use></svg>` (sprite approach)

This would improve:
- Maintainability (edit once, update everywhere)
- Caching (browser caches icon files separately)
- File size (eliminate duplicate SVG code)

## Icon Inventory
- Star (outline) - Hero, achievements, success  
- Rocket - Deploy, launch, progress
- Lightning - Speed, energy, quick actions
- Microphone - Show & tell, presentations
- Clock - Time, duration, scheduling
- Robot - AI automation, coding assistance
- Smiley - Engagement, positivity, feedback
- Calendar - Daily use, scheduling
- Lock - Security, My AI Portal
- Target - Goals, direction, focus
- And 50+ more contextual icons...

Last updated: December 1, 2025
