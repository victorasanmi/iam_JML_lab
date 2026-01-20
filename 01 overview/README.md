# IAM JML Lab

This folder provides a high level overview of the Joiner Mover Leaver lab.

The goal is to demonstrate basic IAM lifecycle thinking using Active Directory.
This lab demonstrates a Joiner, Mover, and Leaver lifecycle implemented in Active Directory using role based access control.

Key points:
- Users are assigned to role groups only
- Role groups are nested into application access groups
- Access changes are driven by lifecycle events, not manual app assignments

## Evidence

Screenshots showing the Joiner, Mover, and Leaver scenarios are available in:
05 evidence / screenshots go here

The evidence includes:
- Group and OU structure
- Role to application group nesting
- Joiner account creation
- Mover role change
- Leaver account disablement and access removal

## What this proves

This repository demonstrates practical IAM lifecycle control in Active Directory.

It proves that I can:
- Design role based access using role groups and application groups
- Implement group nesting so users are never assigned application access directly
- Execute Joiner, Mover, and Leaver events with clear operational steps
- Capture evidence of access changes in a repeatable, auditable way
