# Access model

This document describes how access is structured in the Active Directory lab.

## Design principles

- Users are assigned to role groups only
- Role groups (RG) represent job function
- Application groups (AG) represent system access
- Role groups are nested into application groups
- Users are never assigned directly to application groups

## Role to application mapping

Analyst  
- AG M365  
- AG Jira  

Manager  
- AG M365  
- AG Jira  
- AG HR  

Finance  
- AG M365  
- AG HR  
- AG Finance  

## Lifecycle behaviour

Joiner  
A new user is added to a single role group based on their job role.

Mover  
A role change is handled by removing the old role group and assigning a new one.

Leaver  
Access is removed by disabling the account, removing role group membership, and moving the user to a disabled users OU.
