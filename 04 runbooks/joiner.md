# Joiner runbook

## Purpose
Create a new user account with the correct access based on role.

## Trigger
New starter approved with a defined job role.

## Preconditions
- User details provided
- Role confirmed (Analyst, Manager, or Finance)

## Steps
1. Create the user account in Active Directory.
2. Place the user in OU MapleCo Users.
3. Assign the user to one role group only.
4. Do not assign application groups directly.
5. Verify inherited access via role group nesting.

## Outcome
User has access appropriate to their role through group inheritance.

## Evidence
Screenshots stored in the evidence folder.
