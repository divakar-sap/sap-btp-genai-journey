✅ Day 5

# Entitlements vs Quotas
- Entitlement = permission to use a service at subaccount level.
- Quota = numeric limit within that entitlement (eg., 1 unit of HANA Cloud).

## What i did
- Reviewd HANA Cloud entitlement + quota

✅ DAy 6

# MM APIs Explored (API Business Hub)

## API_PURCHASEORDER_PROCESS_SRV
- Entities : MaterialDocument , MaterialDocumentItem
- Map to MIGO/GR postings I know from SAP GUI

## API_BUSINESS_PARTNER
- Vendor master data exposed as Business Partner entities

## API_VENDOR_INVOICE_SRV
- Maps to MIRO invoice verification

✅ BTP App (check the structure in code)  
    |
    |-- Authenticated via -> IAS/ Trust configuration
    |
    |-- Authorized via -> Role Collection -> Roles
    |
    |-- Connects to S/4 MM via -> Destination
                                        |
                                -------------------------
                                |                       |
                            Internet                OnPremise (via Cloud Connector)
                            (direct)                    |
                                |                     [On-Prem S/4HANA MM]
                            [Sandbox/ Cloud]
                                        S/4
    


