To use:
1. In your project settings make sure you edit you configuration and set the `SecretsManager.EncryptionKey` constant to a 32 character encryption key.
3. Add the `Manage_Secrets` page to your navigation, or if you want to add your own layout, copy it to your project and modify as needed.
4. Assign the users who can create and edit key/secret(username/password) pairs the `SecretsManagement.Admin` role.
5. For users who can access key/secret(username/password) pairs but not create new ones, assign the `SecretsManager.User` role.
6. Then to use the key/secret(username/password) pair you can use the microflow `ACT_GetDecryptedCredentials`. 
