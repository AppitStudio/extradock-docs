Import / Export
===============

Use Import / Export to back up your ExtraDock setup, restore it later, or move it to another Mac.

Open **Settings** (⚙) → **Import / Export**.

Local Backup
------------

A full backup uses the ``.extradockbackup`` format. It includes your docks, dock items, widgets, settings, and custom icons.

To export:

1. Open **Settings** (⚙) → **Import / Export**
2. Click **Export...**
3. Choose where to save the backup

To import:

1. Open **Settings** (⚙) → **Import / Export**
2. Click **Import...**
3. Choose a ``.extradockbackup`` file
4. Review the docks in the import wizard
5. Choose whether to import docks as new, replace matching docks, or skip them

Importing does not change anything until you confirm the final step.

Automatic Backups
-----------------

ExtraDock keeps one local dock configuration snapshot per day for the last 7 days.

The **Automatic Backups** section shows how many backups are available. You can:

- **Refresh** — Reload the backup list
- **Reveal** — Open the backup folder in Finder
- **Restore** — Replace the current setup with a selected backup

When restoring an automatic backup, ExtraDock makes a snapshot of your current configuration first.

DockShare packages
------------------

The **DockShare** section exports a public-safe ``.extradockshare`` package for publishing shared dock layouts.

DockShare packages are designed to avoid leaking private paths and widget data. Use a full backup for personal restore/migration, and DockShare export for public sharing.

See :doc:`dockshare` for sharing details.
