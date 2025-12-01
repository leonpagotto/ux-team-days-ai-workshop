# IKEA Design System Icons

This folder contains official IKEA design system icons for use in presentations and prototypes.

## Available Icons

### Status & Feedback
- `checkmark.svg` - Confirmation / success
- `star.svg` - Outlined star / rating
- `star-filled.svg` - Filled star / favorite
- `warning-triangle.svg` - Warning / alert
- `information-circle.svg` - Info / help
- `question-mark-circle.svg` - Question / help

### Navigation & Actions  
- `play.svg` - Play / start
- `pause.svg` - Pause
- `arrow-trend-up.svg` - Growth / progress
- `magnifying-glass.svg` - Search

### Objects
- `clock.svg` - Time / duration
- `laptop.svg` - Computer / device
- `document.svg` - File / document
- `folder.svg` - Folder
- `pencil.svg` - Edit / write
- `gear.svg` - Settings

### People & Communication
- `people.svg` - Team / group
- `person-small.svg` - Individual person
- `chat.svg` - Communication / chat
- `hand-gestures.svg` - Hand gestures
- `thumbs-up.svg` - Approval / like
- `thumbs-down.svg` - Disapproval / dislike

### Nature & Elements
- `globe.svg` - World / international
- `flame.svg` - Fire / hot / trending
- `lightbulb-with-rays.svg` - Idea / inspiration
- `crosshair.svg` - Target / focus

### System
- `network.svg` - Network / connection

## Usage

Reference icons in your HTML:
```html
<img src="icons/checkmark.svg" alt="checkmark" width="24" height="24">
```

Or inline the SVG for color customization:
```html
<svg viewBox="0 0 24 24" width="24" height="24">
  <path fill-rule="evenodd" clip-rule="evenodd" d="M19.707 7.7072 10 17.4142l-5.707-5.707 1.4142-1.4142L10 14.5858l8.2928-8.2928 1.4142 1.4142z" fill="#00853F"/>
</svg>
```

## IKEA Icon Format

All IKEA icons use:
- `viewBox="0 0 24 24"` - Standard 24x24 grid
- `fill-rule="evenodd" clip-rule="evenodd"` - For complex paths
- Solid fills (not strokes) for the main path

## Current Presentation Icons

The presentation currently uses custom inline SVGs with stroke-based designs. These can be gradually replaced with official IKEA icons using the fill-based format.

### Icon Path Reference

**Checkmark (IKEA format):**
```svg
<path fill-rule="evenodd" clip-rule="evenodd" d="M19.707 7.7072 10 17.4142l-5.707-5.707 1.4142-1.4142L10 14.5858l8.2928-8.2928 1.4142 1.4142z" fill="#FBD914"/>
```

**Star Filled (IKEA format):**
```svg
<path d="m12.0025 4 2.8593 4.9091 5.5524 1.2024-3.7852 4.2363L17.2012 20l-5.1987-2.2909L6.8038 20l.5723-5.6522-3.7853-4.2363 5.5524-1.2024L12.0025 4z"/>
```

**Clock (IKEA format):**
```svg
<path fill-rule="evenodd" clip-rule="evenodd" d="M19.9969 12c0 4.4187-3.5821 8.0008-8.0008 8.0008-4.4187 0-8.0008-3.5821-8.0008-8.0008 0-4.4187 3.582-8.0008 8.0008-8.0008 4.4187 0 8.0008 3.582 8.0008 8.0008zm1.9992 0c0 5.5228-4.4772 10-10 10-5.5229 0-10-4.4772-10-10 0-5.5229 4.4771-10 10-10 5.5228 0 10 4.4771 10 10zM10.9926 6.0062v5.8154L7.3102 15.273l1.3671 1.4587 3.9985-3.7476.316-.2962V6.0063h-1.9992z"/>
```

## Source

Icons from the IKEA design system: `/Files/Icons/` in the leo-docs repository.

Last updated: December 1, 2025
