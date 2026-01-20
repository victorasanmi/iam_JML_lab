# Build steps

This document records the key implementation steps for the IAM Joiner Mover Leaver lab.

## Environment setup
- Active Directory Domain Services configured
- Organisational Units created for users, groups, and disabled accounts
- Role groups and application groups created with clear naming

## Access model implementation
- Role groups created: Analyst, Manager, Finance
- Application groups created: M365, Jira, HR, Finance
- Role groups nested into application groups
- Users assigned to role groups only

## Lifecycle events executed

| Event   | Action taken | Evidence |
|--------|--------------|----------|
| Joiner | User created and assigned to role group | Screenshots |
| Mover  | Role group changed from Analyst to Finance | Screenshots |
| Leaver | Account disabled, access removed, user moved to disabled OU | Screenshots |
