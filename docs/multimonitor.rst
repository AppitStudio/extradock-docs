Multi-Monitor
=============

ExtraDock is built for multi-monitor setups. Each dock can be assigned to a specific display and remembers which screen it belongs to.

Assigning a dock to a screen
-----------------------------

- **Right-click** the dock → **Display** → choose a screen
- **Management window** → **Properties** → **Position** → **Screen** → **Choose Screen**

The screen picker shows all connected displays with their names. If you have multiple identical monitors, ExtraDock disambiguates them automatically.

Attach to screen
----------------

When **Attach to Screen** is enabled, the dock is bound to its assigned display:

- If that display disconnects, the dock hides automatically
- When the display reconnects, the dock reappears in its original position

When disabled (the default), a dock moves to the main display if its preferred screen disconnects.

**Management window** → **Properties** → **Position** → **Attach to Screen**

Disconnect and reconnect
------------------------

ExtraDock uses stable display identifiers (based on vendor, model, and serial number) so your docks reliably return to the right screen — even after unplugging and replugging monitors.
