# Case Study 2: Managing Storage Access with Stored Access Policies

Your organization requires a more manageable approach to granting temporary access to storage containers. Instead of generating individual SAS tokens, you need to implement a stored access policy that can be modified or revoked as needed.

## Task:

- Create a stored access policy on a container within your Azure Storage account. This policy should grant read and list permissions for a specific time range.
- Generate a SAS token associated with the stored access policy.
- Demonstrate how to use the SAS token to access the container.
- Modify the stored access policy to revoke access, and then attempt to use the SAS token again.

## Skills Tested:

- Create and use shared access signature (SAS) tokens
- Configure stored access policies

## Tools:

For this exercise, I recommend using the Azure CLI.

Before you begin, would you like a quick refresher on how to create stored access policies or generate SAS tokens associated with them?

Once you've completed the task, explain how modifying the stored access policy affects the validity of the SAS token. What happens when you try to use a SAS token after revoking its associated policy?
