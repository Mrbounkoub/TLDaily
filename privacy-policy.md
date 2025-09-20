# Privacy Policy for TLDaily
_Last updated: 2025-09-20_

## Summary
TLDaily does not transmit data to any server. All processing happens locally in your browser.

## Data the extension can read (locally only)
- On Airtable task dialogs: visible fields such as **Task Name**, **Asana Link**, **Task ID**, **Customer Email**, and **Client Report**.
- On Ziflow proof pages: visible input areas to help paste previously copied data.

This reading is used only to show/copy/fill data you see on those pages.

## What we store (in `chrome.storage`)
- **Settings:** your name, date/name **format pattern**, and toggles (Enable, Auto-scrape, Show MAA).
- **Last snapshot (optional):** most recent task details (Task Name, Asana Link, Task ID, Customer Email, MAA) cached **locally** to transfer into Ziflow on your request. This snapshot is overwritten frequently and never leaves your device.

You can clear this via Chrome > Clear browsing data > “Hosted app data” or by removing the extension.

## Clipboard
We write to the clipboard **only when you click copy**. No background copying.

## Permissions we use & why
- `storage` — Save local preferences (name, format pattern, toggles) and the last task snapshot.  
- `tabs` — Find Airtable/Ziflow tabs to apply settings and open the **New proof** page in a new tab. We **do not** read your history.  
- `activeTab`/`scripting` — Run the content script on the current Airtable/Ziflow page to read visible fields and assist pasting.  
- `clipboardWrite` — Copy selected fields when you click copy.  
- **Host permissions:** `airtable.com` and `ziflow.io` only, to interact with those pages.

## Data sharing
- No analytics, no tracking, no ads.
- No selling or sharing of data with third parties.

## Security
- All operations run inside Chrome’s extension sandbox.
- Data never leaves your machine.

## Changes
We may revise this policy. We’ll update the “Last updated” date above.

## Contact
Questions or requests: **[add your contact/email here]**
