To use:
1. For SecretsManager version 1.0.0, Encryption module version 8.0.6 is required.
2. In your project settings make sure you edit you configuration and set the `SecretsManager.EncryptionKey` constant to a 32 character encryption key.
3. Add the `Manage_Secrets` page to your navigation, and assign the users who can manage secrets the `SecretsManagement.Admin` role.
4. For users who can access secrets but not create new ones, assign the `SecretsManager.User` role.
5. Then to use the secret you can use the microflow `ACT_GetDecryptedCredentials`. 
