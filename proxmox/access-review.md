# Access Review Process

## Purpose

This document defines a simple access review process for the Proxmox lab environment.

## Review Checks

During an access review, I would verify:

- Is the user still active?
- Does the user still require access?
- Is the assigned role appropriate for their current responsibilities?
- Does the user have more privilege than required?
- Are privileged accounts still necessary?
- Are any unused or stale accounts present?

## Joiner Process

When a new user requires access:

1. Create the user account.
2. Assign the user to the appropriate role-based group.
3. Apply the minimum permissions required.
4. Test the account.
5. Record the access granted.

## Mover Process

When a user's responsibilities change:

1. Review their existing group memberships.
2. Remove permissions that are no longer required.
3. Add the user to the appropriate new group.
4. Re-test access.
5. Document the change.

## Leaver Process

When a user leaves:

1. Disable or remove the account.
2. Remove all group memberships.
3. Revoke privileged access.
4. Confirm the account can no longer authenticate.
5. Review logs for any recent privileged activity.

## Review Frequency

In a production environment, access should be reviewed periodically and after significant role changes.

The aim is to prevent privilege accumulation and ensure access remains aligned with business need.