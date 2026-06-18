💠BTP: Buisness Technology Partner
BTP account follows below architecute :
✅ Global Account 
    This is company's BTP contract.  
    It is the highest orgazinational entity in the platform's hierarchy.
    It is as the ultimate root container for everything done on the platform.
    It does not host any applications or databases, instead it acts as a parent container.  
    Within global account, Directories and Subaccounts are setup.
    ✅Directories:  
        It is optional. used to group subaccounts based on functional, regional or orgazinational criteria for easier management.  
        There can be multiple directories as needed, but SAP enforces a nesting depth limit. it can be maximum 7 levels deep (including subaccount at very end of chain).  
    ✅Subaccounts:  
        The actual environments where applications are deployed, services are instantiated and users are given access.
        There can be multiple subaccounts under one directory, eg: development environment, testing environment, production environment.  
        ✅Under subaccount there are:  
            Cloud Foundry Environment: it includes the spaces where apps actually run.
            KYMA Environment: Kubernetes
            Services: There are multiple services available like HANA cloud, AI core etc.  
to gist out everything in MM terms:  
Global Account is whole SAP landscape system.  
Subaccounts are multiple clients available like DEV, PRD.
Space is development environment within client.  
Services are like t-codes/modules activated per client.  
