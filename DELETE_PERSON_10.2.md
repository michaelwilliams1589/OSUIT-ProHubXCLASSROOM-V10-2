# Delete Person 10.2

The account-removal workflow now completes without reading `/courseMembers`.

It removes:
- Pro Hub profile
- Role
- Faculty request
- User course index
- Personal calendar
- Sports, entertainment, widgets, tasks, notes, and quick links
- Notebooks and templates
- Home profile, notes, and reminders

It also writes the UID to `blockedAccounts` so the account cannot re-enter the workspace.

Course membership records are not scanned or deleted in this version.
