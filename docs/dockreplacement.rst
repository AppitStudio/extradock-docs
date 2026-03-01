Using ExtraDock as a Dock Replacement
======================================

ExtraDock can fully replace the native macOS Dock. Here's how to set it up and which features cover what the built-in Dock does.

Hiding the native Dock
-----------------------

Open **Settings** (⚙) → **General** → toggle **Hide native macOS Dock**. ExtraDock suppresses the built-in Dock while the app is running. Turn this off anytime to bring it back.

See :doc:`general` for details.

Matching native Dock features
------------------------------

The macOS Dock provides a set of core features. Here's how ExtraDock covers each one:

**Launching apps**

Drag apps into any dock or use the **+ Add** button. See :doc:`addingapps`.

**Running indicators**

A dot appears on each running app's icon, just like the native Dock. See :doc:`runningindicators`.

**Notification badges**

Red badge counts appear on app icons for unread notifications. See :doc:`notificationbadges`.

**Drag and drop**

Drag files onto app icons to open them with that app. See :doc:`dragdrop`.

**Folders**

Drag folders into a dock for quick access. Folders can display their name below the icon. See :doc:`folderdisplay`.

**Trash**

Add the :doc:`Trash widget <widgets>` to any dock for drag-to-trash and empty-trash functionality.

**Finder access**

Add the :doc:`Finder widget <widgets>` to open Finder windows from the dock.

**App actions**

Right-click any app icon to quit, hide, or reveal it in Finder. See :doc:`appactions`.

**Auto-hide**

Docks can auto-hide and reappear on hover, with configurable delays. See :doc:`autohide`.

**Position on screen**

Pin a dock to any edge — bottom, left, right, or top — or leave it floating anywhere. See :doc:`fixed` and :doc:`floating`.

Tracking running apps with Live Dock
--------------------------------------

The native Dock shows running apps with a small dot — but you still have to remember what's open. The :doc:`LiveDock <widgets>` widget solves this by giving you a dock that updates itself automatically.

Live Dock has two modes:

- **Running Apps Only** — The dock only shows apps that are currently running. Apps appear when launched and disappear when quit. This turns a dock into a live task switcher — you always see exactly what's open, nothing more.

- **Full Dock** — Mirrors your macOS Dock contents including persistent apps, folders, and files. This is useful if you want a second copy of your Dock layout on another screen or edge, without manually recreating it.

For a full replacement workflow, **Running Apps Only** on a second dock works well alongside a primary dock of pinned apps. You get a clean separation: one dock for launching, one for managing what's running.

See :doc:`LiveDock <widgets>` for setup details.

Knowing what's in your current Space
--------------------------------------

If you use multiple macOS Spaces (virtual desktops), it's easy to lose track of which apps have windows in the Space you're currently on. The :doc:`Space Awareness <widgets>` widget shows exactly that — it displays icons for apps with windows in the active Space, updating as you switch between them.

This is especially useful in a dock replacement setup where you have several Spaces for different tasks. Instead of opening Mission Control to see what's where, you get that information right in your dock.

Going beyond the native Dock
------------------------------

Once you've replaced the built-in Dock, ExtraDock opens up more features macOS doesn't offer:

- **Multiple docks** — Separate docks for different workflows or screens (:doc:`creating`)
- **Multi-monitor** — Assign docks to specific displays (:doc:`multimonitor`)
- **Widgets** — Clock, IP address, Stripe revenue, and more (:doc:`widgets`)
- **Collapse mode** — Minimize a dock to a single icon (:doc:`collapse`)
- **Global hotkeys** — Show/hide any dock with a keyboard shortcut (:doc:`hotkeys`)
- **Custom icons** — Replace any icon with your own (:doc:`customicons`)
- **Visual effects** — Snow and fireworks overlays (:doc:`effects`)
- **Vertical docks** — Rotate any dock to vertical orientation (:doc:`orientation`)

Recommended setup
-----------------

A minimal replacement setup:

1. Create a primary dock and pin it to the bottom edge — add your most-used apps (:doc:`fixed`, :doc:`addingapps`)
2. Add the Trash and Finder widgets (:doc:`Trash widget <widgets>`, :doc:`Finder widget <widgets>`)
3. Create a second dock with the Live Dock widget set to **Running Apps Only** (:doc:`LiveDock <widgets>`)
4. Enable notification badges (:doc:`notificationbadges`)
5. Hide the native Dock (:doc:`general`)

From there, add more docks, widgets, or a Space Awareness indicator as you see fit.
