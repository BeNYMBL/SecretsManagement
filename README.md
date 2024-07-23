To use:
1. For SecretsManager version 1.0.0, Encryption module version 8.0.6 is required.
2. In your project settings make sure `Encryption.Encryption` key constant has a 32 character encryption key.
3. For each secret/password or API Key that you want to share, add a new value to the enumeration `SECRET_NAME`
4. Add the `Manage_Secrets` page to your navigation, and assign the users who can manage secrets the `SecretsManagement.Admin` role.
5. For users who can access secrets but not create new ones, assign the `SecretsManager.User` role.
6. Then to use the secret you can use the microflow `ACT_GetDecryptedCredentials`.  
