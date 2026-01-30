# Picviewer Simple

**Install Link:** [GreasyFork - Picviewer Simple](https://greasyfork.org/en/scripts/559994/)

---

## Short Summary

**Picviewer Simple** is a lightweight userscript designed to enhance your image viewing experience. It adds a small magnifier icon over every `<img>` element when you hover your mouse over it. Clicking the icon opens a streamlined viewer where you can zoom, rotate, and reset the image. The controls (zoom in/out, rotate left/right, reset, close) are always pinned to the top for easy access.

---

## Installation

1. Install a userscript manager like **Tampermonkey** or **Greasemonkey** for your browser.
2. Go to the [GreasyFork link](https://greasyfork.org/en/scripts/559994/) and click **"Install this script"**.
3. Alternatively, create a new userscript in your manager and paste the code from `Picviewer Simple.user.js`.
4. Reload your tabs. Hover over any image to see the magnifier icon and click it to open the viewer.

---

## Features

* **Hover-Triggered Icon:** A magnifier icon appears on every `<img>` element (no site-specific hacks needed).
* **Flexible Activation:** Open the viewer by:
    * Clicking the magnifier icon.
    * Double-clicking the image.
    * **Double Alt Key Shortcut:** Hover over an image and press the `Alt` key twice in quick succession.
    * **Alt + Hover:** Holding the `Alt` key while moving the mouse over images will also trigger the viewer instantly.
* **Intelligent Positioning:** Automatically positions the icon outside the image bounds for small images (<100px) to ensure visibility and prevent obstruction.
* **Extension Menu Settings:** Toggle the hover icon on/off directly from your userscript manager's menu (Tampermonkey/Violentmonkey).
* **Comprehensive Controls:**
    * **Zoom:** via buttons or mouse wheel.
    * **Rotate:** Left or right using dedicated buttons.
    * **Persistent UI:** Controls stay on top (z-index managed), so they remain clickable even when the image is zoomed or rotated.

## Shortcuts
* `Esc`: Close viewer
* `+` / `-`: Zoom in/out
* `[` / `]`: Rotate left/right
* `0`: Reset view
* `Alt` (x2) while hovering: Open viewer
* `Alt` (hold) + hover: Open viewer
* `Double click`: Open viewer

## Customization

You can tweak the script's appearance at the top of the code, or use the **Extension Menu** for common settings:

* `ENABLE_HOVER_ICON`: Set to `false` to hide the icon (can also be toggled via the extension menu).
* `ICON_SIZE`: Change the size of the magnifier icon (px).
* `RIGHT_OFFSET`: Adjust the icon's distance from the right edge (px).
* `ICON_RAISE_PX`: Adjust the icon's height from the bottom corner (px).

---

## Changelog

### v1.5
- **New Feature:** Added Extension Menu Settings to toggle the hover icon on/off.
- **Improved:** Robust Alt key detection (prevents browser menu interference).
- **Improved:** Intelligent icon positioning (moves outside for images < 100px).
- **Update:** Changed activation logic to support both Double Alt and Alt-Hold-Hover.

### v1.2
- **New Feature:** Added Double Alt key shortcut to open viewer.
- **Improved:** Better image tracking for dynamic content.

### v1.1
- **Initial Release:** Simple image viewer with zoom/rotate controls and hover icon.

---

## Notes

* **Lightweight:** Designed to be minimal and fast with no site-specific bloat.
* **License:** Distributed under the **GPL-2.0** license.