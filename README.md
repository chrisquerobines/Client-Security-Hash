# Client-Security-Hash
UiPath Advance RPA Developer : Calculate Client Security Hash

This process was done using UiPath REFramework. 

Process Description:

1. Open ACME System1 Web Application (IExplorer, default browser)

2. Login to web applications using Orchestrator assets (credentials).

3. Navigate to dashboard and select Work Items.

3. Filter work items that needs to be processed and select Client Information Details

4. Open SHA1 Online website.

5. Input ClientID-ClientName-ClientCountry details and retrieve Hash value

6. Update Client Information Details with Hash Value in the comment and set status as "Completed"

7. Proceed next Work Item (WI5).

