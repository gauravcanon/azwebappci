Service Principal

https://learn.microsoft.com/en-us/cli/azure/create-an-azure-service-principal-azure-cli?view=azure-cli-latest#create-the-service-principal
https://docs.microsoft.com/en-us/azure/active-directory/develop/howto-create-service-principal-portal

```shell
$ az ad sp create-for-rbac --name "myApp" --role contributor --scopes /subscriptions/00000000-0000-0000-0000-000000000000
```
```shell
$ az ad sp create-for-rbac --name CICD-SP --role Contributor --scopes /subscriptions/[SUBSCRIPTION-ID]/resourceGroups/[RESOURCE-GROUP-NAME] --sdk-auth
```

