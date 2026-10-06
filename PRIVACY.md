# Privacy policy — icloud-gcal-sync

icloud-gcal-sync is a personal, self-hosted tool. It is run only by its owner,
for their own accounts.

- **What it accesses:** events from the owner's iCloud calendars (read-only, via
  CalDAV) and the owner's Google Calendar (to create, update and delete the
  mirrored events it created).
- **Where data goes:** event data is copied from iCloud to the owner's own Google
  Calendar. It is not sent to any other service, sold, shared, or used for
  advertising or analytics.
- **What is stored:** an OAuth refresh token (`token.json`) and an optional local
  cache of calendar data (`state.sqlite`), both on the machine that runs the tool.
- **Revoking access:** remove the app at https://myaccount.google.com/permissions
  and delete the app-specific password at https://appleid.apple.com.
