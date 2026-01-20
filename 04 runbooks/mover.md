# Mover runbook

## Purpose
Update user access when a role or department change occurs.

## Trigger
Approved internal transfer or role change.

## Preconditions
- New role confirmed
- Any required approvals obtained (for example Finance access)

## Steps
1. Identify the user account.
2. Remove the user from the existing role group.
3. Add the user to the new role group.
4. Do not modify application groups directly.
5. Verify access through role group inheritance.

## Outcome
User access reflects the new role, with previous access removed.

## Evidence
Screenshots and approval evidence stored in the evidence folder.
