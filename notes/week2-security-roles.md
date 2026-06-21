# BTP Security Basics.

## Key Concepts
- User: login identity (like SU01)  
- Role: technical permission set defined by app
- Role collection: bundle of role assigned to users (like PFCG composite role)

## What I did
- Explored Business_Application_Studio_Developer role collection
- Created empty role collection : MM_BTP_Learner


✅✅ Day 2:

## Identity Authentication

- BTP subaccounts trusts and identity provider (default or custom).
- This is the basis for login/SSO across S/4, BTP, SuccessFacotrs
- Trust Configuration in cockpit shows which IDp is active. (in my case Default Identity Provider).

✅✅✅ Day 3:

# Destinations - BTP to S/4HANA connection

## Concept
A Destination stores connection details (URL, Auth) so BTP apps don't hardcode credentials. Sane idea as RFC connections (SM59) in classic SAP.

## Key fieds 

- Proxy Type: Internet (Public) vs OnPremise (needs Cloud Connector)
- Authentication: Basic, OAthe2ClientCredetials, PricipalPropagation.
- URL, Type (HTTP etc).

## What i built
- Created destination "ES5_MM_Sandbox" pointing to sandbox.api.com
- Verifies connection successfully

## MM Conneciotn
This is exactly how i'll later connect to real S/4 MM APIs like API_PURCHASEORDER_PROCESS_SRV in Phase 2.


