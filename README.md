# HabitTracker
This is the only desktop app you will ever need
Release [version] — User Facing Improvements and Visual Refresh

Summary
Polished UI updates, new habit-tracking features, and quality-of-life improvements to make logging faster and the app more distinctive.

Highlights
- Progress bar: animated daily completion bar with contextual messages.
- Week strip: persistent 7-day row with tappable days for quick logging.
- Categories: color-coded habit categories with automatic filter UI.
- Calendar heat fill: proportional day fills reflecting completion rate.

Details
Major New Additions
- Progress bar: animated fill and contextual messages.
- Week strip: always-visible 7-day row; tap to log.
- Categories: color-coded dots and filter row when multiple categories exist.
- Calendar heat fill: proportional green fills per day.

Quality of Life Improvements
- Drag to reorder habits using the ⠿ handle.
- Streak badges: shows 🔥 N when active, dash when zero.
- Delete button: hidden until hover; red on hover with ✕ icon.
- Settings: gear icon replaces the old "S".

Visual Upgrades
- New fonts: DM Serif Display and DM Sans.

Upgrade Notes
- Add new fonts to assets and update CSS.
- Ensure backend exposes normalized completion values for heat fills.
- Verify accessibility and reduced-motion fallbacks.

Testing
- Validate logging via week strip, reordering, category filtering, and calendar fills.
- Cross-platform font and hover behavior checks.

Known Issues
- Week strip compression on narrow screens; performance considerations for large habit sets.

Please fork and report any issues found. Thank you.
