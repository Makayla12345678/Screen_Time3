# System Patterns

## Architecture
- Single Page Application (SPA) contained in one HTML file.
- Embedded CSS for styling.
- Embedded JavaScript for logic.

## Key Technical Decisions
- **Storage**: `localStorage` is used to persist the streak count and the date of the last completion.
- **Date Handling**: `Date().toDateString()` is used to compare dates (ignores time component).
- **Styling**: CSS Variables (custom properties) for theming.

## Component Relationships
- `index.html` contains:
    - DOM Structure (Container, Fire Icon, Streak Text, Buttons).
    - Styles (Dark theme, Animations).
    - Script (Logic for persistence and updates).
