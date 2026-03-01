Widgets
=======

Widgets are special dock items that go beyond app shortcuts. They add functionality like clocks, file shelves, URL bookmarks, and more directly into your dock.

Adding a widget
---------------

1. Open the management window → select a dock → **Items** tab

2. Click the **+** button

3. Choose a widget from the widget picker

Each widget has its own settings — click the gear icon on a widget in the Items tab to configure it.

--------------

Spacer
------

Adds adjustable empty space between items in a dock. Use it to visually group items.

- **Size** — Choose from presets (10px, 30px) or set a custom pixel value

Divider
-------

Adds a visible separator line between items in a dock. It adapts automatically to horizontal or vertical orientation.

- **Line color** — Customize the divider's color

--------------

URL
---

Adds a clickable URL shortcut to your dock. Click it to open the URL in your default browser.

1. Add a URL widget from the widget picker

2. Enter the URL — any scheme is supported (``https://``, ``mailto:``, ``tel:``, etc.)

3. URLs without a scheme automatically get ``https://`` prepended

**Icon display**

Two icon modes are available:

- **Favicon** (default) — Automatically fetches the website's favicon
- **SF Symbol** — Choose from the built-in symbol picker when favicon is disabled

**Color presets**

Quick color preset buttons: Blue, Green, Red, Orange, Purple, Light, Dark. You can also set custom icon and background colors.

**Title display**

Enable **Show Title** to display a label below the icon. When enabled, the icon shrinks to 70% size to make room for the text. The title defaults to the domain name — set a custom title in widget settings.

**Context menu**

Right-click the URL widget for:

- **Open URL** — Open in default browser
- **Copy URL** — Copy the URL to clipboard

--------------

Finder
------

Quick access to Finder at a configured location. Click it to open Finder at your chosen directory.

- **Location** — Set the folder path that opens when you click the widget

Trash
-----

Adds a trash can to your dock. Two modes are available:

- **Native macOS Trash** — Works with the system trash. Drag files onto it to move them to the macOS Trash.
- **Virtual Trash** — ExtraDock's own trash with a built-in file browser for managing trashed items.

Shelf
-----

A temporary file storage area built into your dock. Drag files in, store them temporarily, and drag them out to another destination — similar to apps like Yoink or Dropover.

- **Drag in** — Drag files from Finder onto the Shelf widget icon
- **Click** to open a panel showing all stored files
- **Drag out** — Drag files from the panel to any destination
- **Remove** — Delete files from the shelf

Files persist across app restarts until you remove them.

--------------

Clock
-----

Displays a live digital clock in your dock. Configure the time format and display options in the widget settings.

IP Address
----------

Displays your public IP address in the dock. The widget fetches your IP from an external service and refreshes automatically at a configurable interval. Supports both horizontal and vertical dock layouts.

--------------

LiveDock
--------

Mirrors your macOS Dock or shows currently running apps in real time.

**Modes**

- **Running Apps Only** — Shows only apps that are currently running, like a task switcher
- **Full Dock** — Mirrors the complete macOS Dock including persistent apps, folders, and files

LiveDock monitors app launches and quits in real time using macOS notifications — no polling. Running indicators and notification badges are shown when enabled globally.

**Interactions**

- **Click** an app icon to activate it (if running) or launch it (if not)
- **Click** a folder to open it in Finder
- **Right-click** for Hide, Quit, or Reveal in Finder

Space Awareness
---------------

Shows apps that have windows in the current macOS Space (virtual desktop). As you switch between Spaces, the widget updates to reflect which apps are active in each one — a quick alternative to checking Mission Control.

--------------

TamaDocky
---------

A virtual pet cat that lives in your dock. Take care of it and watch it react with different animations.

- **6 animations** — Idle, Idle2, LayDown, Sleepy, Waiting, Surprised
- **8 pet skins** — Choose a look for your cat
- **15 room backgrounds** — Set the scene behind your pet
- **Pet stats** — Happiness, hunger, and energy levels change over time

Click or hover over TamaDocky to see different reactions. The pet's stats affect which animations play — a happy, well-fed cat behaves differently from a hungry, tired one.

Open the widget settings to choose your pet's skin and room background.

--------------

Stripe
------

Displays revenue data from your Stripe account directly in your dock. Designed for developers and business owners who want a quick glance at their numbers.

1. Open **Settings** (⚙) → **Integrations**

2. Enter your Stripe API key (see :doc:`integrations`)

3. Add a Stripe widget to any dock

The widget caches data locally and fetches only what's missing, keeping API usage minimal.
