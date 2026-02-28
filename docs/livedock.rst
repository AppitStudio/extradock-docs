LiveDock
========

The LiveDock widget mirrors your macOS Dock or shows currently running apps in real time, directly inside an ExtraDock dock.

Modes
-----

- **Running Apps Only** — Shows only apps that are currently running, like a task switcher
- **Full Dock** — Mirrors the complete macOS Dock including persistent apps, folders, and files

Switch modes in the widget settings.

How it works
------------

LiveDock monitors app launches and quits in real time using macOS notifications — no polling. For Full Dock mode, it reads the macOS Dock configuration and watches for changes.

Interactions
------------

- **Click** an app icon to activate it (if running) or launch it (if not)
- **Click** a folder to open it in Finder
- **Right-click** for Hide, Quit, or Reveal in Finder

Running indicators appear on active apps, and notification badges are shown when badges are enabled globally.
