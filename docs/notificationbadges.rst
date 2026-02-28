Notification Badges
===================

ExtraDock can show notification badge counts on app icons — the red number badges you see on the native Dock for apps like Mail, Messages, and Slack.

.. note::

   This feature is in active development. Some apps may not report badge counts reliably.

Enabling badges
---------------

Badges are **disabled by default** and require an explicit opt-in:

1. Open ExtraDock → **Settings** (⚙) → **Notifications**

2. Click **Enable Notification Badges**

3. An explanation modal appears describing what the feature does and why it needs Accessibility permission

4. Click **Enable Feature**

5. Grant Accessibility permission when macOS prompts you

Accessibility permission
------------------------

Badge reading uses the macOS Accessibility API to read badge values from the native Dock. Without this permission, badges cannot be displayed.

**System Settings** → **Privacy & Security** → **Accessibility** → add ExtraDock.

Per-app control
---------------

Once badges are enabled globally, you can toggle them on or off for individual apps in **Settings** → **Notifications**.
