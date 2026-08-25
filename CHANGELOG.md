# Changelog — veldora/ui

All notable changes to `veldora/ui` are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [0.5.0] — 2026-08-25

### Added
- **`footer`** — Responsive site footer with branding, navigation links column, and legal text. Usage: `<x-footer brand="My App" tagline="Built with Veldora"></x-footer>`
- **`rating`** — Interactive star rating component with half-star precision, read-only mode, and accessible radio input backing. Usage: `<x-rating name="score" value="3" max="5"></x-rating>`
- **`switch`** — Toggle switch with label, checked state, and name attribute binding.
- **`pagination`** — Pagination bar with current page, total pages, previous/next links.
- **`skeleton`** — Animated placeholder skeleton loader for loading states.
- **`empty`** — Empty state illustration with title, description, and action slot.
- **`divider`** — Horizontal or vertical separator with optional label.
- **`drawer`** — Slide-in drawer panel (left/right/top/bottom) with overlay and close button.
- **`popover`** — Floating content panel anchored to a trigger element.
- **`confirm`** — Confirm dialog modal with confirm/cancel buttons for destructive operations.
- **`datepicker`** — Native date input with label and Veldora styling.
- **`fileupload`** — Styled drag-and-drop file upload zone.
- **`combobox`** — Searchable select with autocomplete dropdown.
- **`inputgroup`** — Input group with prefix/suffix addons (text or icon).
- **`stat`** — Metric stat card with value, label, icon, and trend indicator.
- **`datatable`** — Interactive table with client-side search, sort, and pagination.
- **`timeline`** — Vertical event list with icon, title, description, and timestamp.
- **`stepper`** — Multi-step wizard indicator with completed, active, and upcoming states.
- **`sidebar`** — Navigation sidebar with logo, nav items, and collapsible sub-menus.
- **`container`** — Responsive max-width wrapper with configurable size and padding.
- Total: **41+ components** available.

### Changed
- All component templates use only native `.veldora.php` syntax — no inline PHP tags, no CDN CSS.
- `php veldora ui:list` and `php veldora add <name>` now use `executeDirect()` — work in **zero-dependency** environments (no Symfony/Console required).

---

## [0.4.0] — 2026-07-15

### Added
- Initial 21 components: `button`, `input`, `textarea`, `select`, `checkbox`, `radio`, `badge`, `alert`, `card`, `modal`, `spinner`, `avatar`, `dropdown`, `navbar`, `toast`, `tabs`, `accordion`, `progress`, `tooltip`, `breadcrumb`, `table`.
- `veldora-ui.css` base stylesheet with `--vui-*` CSS custom properties.
- `ComponentRegistry` class with template definitions for all components.
