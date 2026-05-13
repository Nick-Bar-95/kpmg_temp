## Microsoft Entra

- The controller that "manages" a Microsoft Tenant (MT). A MT is a instance of a
Microsoft Entra ID and acts as a secure and isolated container that's responsible for
user authentication and environments.

- entra.microsoft.com/

- The Users tab are users from the systemusers table in dataverse?

### AE

- Name: KPMG Australia Technology Solutions Pty Ltd
- Tenant ID: bb1ed7c2-d8e2-423d-b0e2-dd7c0ab60190
- Primary domain: HOS.onmicrosoft.com
- Environments:

    ```
    [
        {
            Name: KPMG UON,
            URL: kpmgeducationdemo-uon.crm6.dynamics.com,
            Type: Sandbox,
            Organisation ID: 81a0a858-6e3f-f011-be52-002248e341c7,
            Environment ID: 53acf789-5572-4910-aa2e-79934120a441,
            Managed: Yes
        }
    ]
    ```

### QUT

- Name: KPMG Technology Solutions Pty Ltd
- Tenant ID: fdc4da6a-de44-4605-a536-0fa04714b5bf
- Primary domain: GTToyota.onmicrosoft.com
- Environments: 
    ```
    [
        {
            Name: Payment Scheme Test,
            URL: paymentschemetest.crm6.dynamics.com,
            Type: Sandbox,
            Organisation ID: a1cce09d-f99a-4848-b309-cfcee1791066,
            Environment ID: f172b95c-ed1e-ed00-8802-a09ed0a5b6ce,
            Managed: No
        },
        {
            Name: Payment Scheme Dev,
            URL: payrmentschemedev.crm6.dynamics.com,
            Type: Sandbox,
            Organisation ID: e5775766-5146-4786-a8f7-3993c6327009,
            Environment ID: 72c4df95-23bc-e481-8875-3765ab9429ce,
            Managed: No
        }
    ]
    ```