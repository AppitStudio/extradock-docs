Using ExtraDock as a Dock Replacement
=====================================

ExtraDock can fully replace the native macOS Dock. Here's how to set it up and which features cover what the built-in Dock does.

Hiding the native Dock
----------------------

Open **Settings** (⚙) → **General** → toggle **Hide native macOS Dock**.

ExtraDock suppresses the built-in Dock while the app is running. Turn this off anytime to restore your previous Dock behavior.

Matching native Dock features
-----------------------------

**Launching apps**

Drag apps into any dock or use **Add Item** in the Items tab. See :doc:`addingapps`.

**Running indicators**

A dot appears on each running app's icon, just like the native Dock. See :doc:`runningindicators`.

**Notification badges**

Red badge counts appear on app icons for unread notifications. See :doc:`notifications`.

**Drag and drop**

Drag files onto app icons to open them with that app. See :doc:`dragdrop`.

**Folders and files**

Add folders or files to a dock for quick access. Folders can show labels, use tint colors, and open with Finder or another app. See :doc:`folderdisplay`.

**Trash**

Add the :doc:`Trash widget <trashwidget>` to any dock for drag-to-trash and empty-trash functionality.

**Finder access**

Add the :doc:`Finder widget <finderwidget>` to open Finder windows from the dock.

**App actions**

Right-click any app icon to quit, hide, or reveal it in Finder. See :doc:`appactions`.

Tracking running apps with Live Dock
------------------------------------

The :doc:`Live Dock <livedock>` widget can show running apps or mirror your native macOS Dock.

Live Dock has two modes:

- **Running Apps** — Shows apps that are currently running
- **Full Dock** — Mirrors the native macOS Dock contents

For a full replacement workflow, Running Apps mode works well alongside a primary dock of pinned apps. You get one dock for launching and one dock for managing what's currently open.

Knowing what's in your current Space
------------------------------------

The :doc:`Space Awareness <spaceawareness>` widget shows apps with windows in the current macOS Space.

This is useful when you use several Spaces for different tasks and want to see what belongs to the desktop you're currently using.

App Previews
------------

:doc:`App Previews <apppreviews>` show open windows when you hover over running app icons. They can make ExtraDock feel more like a window switcher, especially when the native Dock is hidden.

Automation
----------

Use :doc:`hotkeys` for direct keyboard access to docks.

Use :doc:`macosshortcuts` to show, hide, or toggle docks from macOS Shortcuts or Focus modes.

Going beyond the native Dock
----------------------------

Once you've replaced the built-in Dock, ExtraDock opens up more features macOS doesn't offer:

- **Multiple docks** — Separate docks for different workflows or screens (:doc:`creating`)
- **Multi-monitor** — Assign docks to specific displays (:doc:`multimonitor`)
- **Widgets** — Clock, IP address, Folder Stack, Shelf, Stripe Balance, and more (:doc:`widgets`)
- **Collapse mode** — Minimize a dock to a single button (:doc:`collapse`)
- **Custom icons** — Replace app, folder, file, and widget icons (:doc:`customicons`)
- **Visual effects** — Snow, Rays, and fireworks overlays (:doc:`effects`)
- **Vertical docks** — Rotate any dock to vertical orientation (:doc:`orientation`)
- **Import / Export** — Back up, restore, or share layouts (:doc:`importexport`)

Recommended setup
-----------------

A minimal replacement setup:

1. Create a primary dock and pin it to the bottom edge — add your most-used apps (:doc:`fixed`, :doc:`addingapps`)
2. Add the Trash and Finder widgets (:doc:`trashwidget`, :doc:`finderwidget`)
3. Create a second dock with Live Dock set to **Running Apps** (:doc:`livedock`)
4. Enable notification badges (:doc:`notifications`)
5. Optional: enable App Previews (:doc:`apppreviews`)
6. Hide the native Dock (:doc:`general`)

From there, add more docks, widgets, hotkeys, or Space Awareness as you see fit.
