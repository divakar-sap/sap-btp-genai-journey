# BTP Security Basics.

## Key Concepts
- User: login identity (like SU01)  
- Role: technical permission set defined by app
- Role collection: bundle of role assigned to users (like PFCG composite role)

## What I did
- Explored Business_Application_Studio_Developer role collection
- Created empty role collection : MM_BTP_Learner

✅Day 2:

## Identity Authentication

- BTP subaccounts trusts an Identity provider (default or custom).
- This is the basis for login/SSO across S/4, BTP, SuccessFacotrs
- Trust Configuration in cockpit shows which IDp is active. (in my case Default Identity Provider).