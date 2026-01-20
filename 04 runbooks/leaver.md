# Leaver runbook

## Purpose
Remove access promptly when a user leaves the organisation.

## Trigger
Employee termination or contract end confirmed.

## Preconditions
- Leaver approval received
- User account identified

## Steps
1. Disable the user account in Active Directory.
2. Remove the user from all role groups.
3. Move the user to OU MapleCo Disabled Users.
4. Do not delete the account.

## Outcome
User access is fully revoked while the account is retained for audit and retention purposes.

## Evidence
Screenshots stored in the evidence folder.
