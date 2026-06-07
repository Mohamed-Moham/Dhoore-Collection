# Upgrade User Management TODO

- [ ] Add centralized dynamic role permission templates (Admin/Manager/Cashier) and normalize loaded roles.
- [ ] Enforce Manager access restrictions (no role management, no admin password change, no backup delete).
- [ ] Enforce Cashier restrictions (sales + receipt printing + product view only; no settings/backup/user management/profit/cost).
- [ ] Keep/upgrade Role Management section for unlimited custom roles in Settings.
- [x] Ensure user creation role dropdown is fully dynamic from stored roles.
- [ ] Enforce default role bootstrap (Admin, Manager, Cashier) and persist when missing.
- [ ] Harden role dropdown population to never be empty.
- [ ] Populate role dropdown reliably on page load.
- [ ] Add "Save User" button to Create Staff User section.
- [ ] Ensure created users are saved and reflected in Staff Accounts table.
- [ ] Test that Admin, Manager, Cashier appear in role dropdown.
- [ ] Save and apply roles/permissions from storage automatically at login.
- [ ] Fix deleteRole user reassignment bug to preserve user objects.
- [ ] Re-render and guard UI/actions by permission at runtime.
