Behavior Settings
=================

Global settings that affect how dock items open, how docks snap, and how fixed docks interact with app windows.

Open **Settings** (⚙) → **Behavior**.

Left click behavior
-------------------

Choose what happens when you click a running app icon:

- **Open** — Activate the app or return to its last used window
- **Minimize** — Toggle the current app window between minimized and restored

Minimize requires Accessibility permission. Without it, clicks fall back to normal open and activate behavior.

See :doc:`leftclick`.

Open folders with
-----------------

Choose the application used when folder dock items are clicked.

By default, folders open in Finder. You can choose another app if you prefer a different file manager.

Magnetic snapping
-----------------

When dragging a floating dock near a screen edge, it magnetically snaps into alignment.

Toggle **Disable magnetic snapping** if you prefer full free-form positioning.

Reserve Dock Space
------------------

When enabled, expanded app windows stay outside the area occupied by your fixed docks. This prevents windows from hiding behind edge-pinned docks.

**Requires Accessibility permission.** ExtraDock uses macOS Accessibility to detect and resize overlapping windows.

Active on Drag
--------------

By default, Reserve Dock Space adjusts windows when they are expanded with the green zoom button or by double-clicking the title bar.

Enable **Active on Drag** to also adjust windows after a manual drag or resize that overlaps a fixed dock.

This option is only available when Reserve Dock Space is enabled.
