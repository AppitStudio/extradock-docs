Multi-Monitor
=============

ExtraDock is built for multi-monitor setups. Each dock can be assigned to a specific display and remembers which screen it belongs to.

Allowed screens
---------------

Open **Management window** → **Properties** → **Position** → **Allowed Screens**.

When no screen is assigned, the dock can appear on any screen.

Use **Add Screen** to limit the dock to one or more known screens. If you have multiple identical monitors, ExtraDock uses live connection details to keep them separate.

How assigned screens work
-------------------------

- A dock can only appear on one screen at a time
- If no assigned screen is connected, the dock hides
- When an assigned screen reconnects, the dock can return to it

If you want the same dock layout on multiple screens at once, duplicate the dock and assign each copy to a different screen.

Forgetting screens
------------------

Use **Forget Screen...** to remove disconnected external displays from ExtraDock's known screen list. Built-in and currently connected screens cannot be forgotten.

Disconnect and reconnect
------------------------

ExtraDock uses stable display identifiers (based on vendor, model, and serial number) so your docks reliably return to the right screen — even after unplugging and replugging monitors.
