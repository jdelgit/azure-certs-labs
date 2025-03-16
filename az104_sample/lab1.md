# Case Study 1: Secure Storage Access for a Development Team

A development team within your organization needs to securely access an Azure Storage account to store and retrieve application logs. You need to provide them with access while adhering to the principle of least privilege.

## Task:

- Create an Azure Storage account.
- Generate a Shared Access Signature (SAS) token that grants the development team read and list access to a specific container within the storage account for a limited time.
- Demonstrate how to use the SAS token to access the container.

## Skills Tested:

- Configure Azure Storage firewalls and virtual networks
- Create and use shared access signature (SAS) tokens

## Tools:

For this exercise, I recommend using the Azure CLI.

Before you begin, please let me know if you'd like any guidance on creating a storage account or generating SAS tokens using the Azure CLI.

Once you've completed the task, describe how you would verify that the SAS token is working correctly. For example, what Azure CLI command could you use?

`az storage blob show --container-name <container_name> --name <blob_name> --account-name <storage_account_name> --sas-token "<sas_token>"`
