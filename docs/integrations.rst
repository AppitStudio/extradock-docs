Integrations
============

Connect ExtraDock to third-party services used by widgets.

Open **Settings** (⚙) → **Integrations** to manage connections.

Stripe
------

The :doc:`stripewidget` needs a Stripe API key to fetch live revenue data.

Connecting your account
^^^^^^^^^^^^^^^^^^^^^^^

1. Click **Open Stripe Dashboard** — this opens the Stripe key creation page with recommended read-only permissions pre-filled

2. Copy the generated key (starts with ``rk_live_``, ``rk_test_``, ``sk_live_``, or ``sk_test_``)

3. Paste it into the **Stripe API Key** field and click **Save Key**

The key is stored securely in your macOS Keychain and is never sent to ExtraDock's servers.

Managing the key
^^^^^^^^^^^^^^^^

Once connected, the integrations page shows the connection status and when the key was last updated. You can:

- **Delete Key** — Removes the key from Keychain. Stripe widgets will stop updating until a new key is added.

Use restricted keys (``rk_``) for the safest read-only access. You can revoke the key anytime from your Stripe dashboard.
