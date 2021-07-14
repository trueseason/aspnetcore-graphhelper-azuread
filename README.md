# AspNetCore.GraphHelper.AzureAD

This is a Azure AD authentication helper to retrieve the user groups from the signed-in user or session. Source code imported from Microsoft's [Azure Samples Repository](https://github.com/Azure-Samples).

## Build

### Tools

- dotnet.exe command line
- Visual Studio / Code

## Usage

Build the library yourself or import the NuGet package.

```c#
async List<string> UsersGroupHelper.GetSignedInUsersGroups(TokenValidatedContext context)

List<string> UsersGroupHelper.GetUserGroupsFromSession(ISession httpContextSession)
```

