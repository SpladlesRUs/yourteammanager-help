# Managing Admin Accounts

Admin Management controls who can access the dashboard and what they can do.

## Adding an Admin

1. Open **Admin Management** from the dashboard.
2. Click **Add Admin** and fill in the name and email.
3. Choose a role to determine their permissions (see *Roles and Permissions* below).
4. Save to send them a welcome email with login details.

## Editing and Removing

- Select an admin to change their information or password.
- Disable an admin by unchecking **Active**; their history remains intact.

## Roles and Permissions

YourTeamManager ships with a set of predefined roles:

- **Sudo Admin** – built-in superuser created during setup. This role cannot be
  reassigned or removed.
- **Owner** – highest assignable role with full editing rights.
- **Coach** – standard editing privileges for assigned rosters.
- **Graduate Assistant** – read-only by default.

Additional custom roles can be created from the **Roles** tab. Each role has a
level that determines its rank and a *Can Edit* flag controlling write
permissions.

## Roster Access and Notifications

Use the **Roster Access** table to assign which rosters an admin can manage. If they are subscribed to email reports, they'll only receive updates for the rosters selected here.