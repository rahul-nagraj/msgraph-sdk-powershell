### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.DeviceManagement

$params = @{
	"@odata.type" = "#microsoft.graph.notificationMessageTemplate"
	displayName = "Display Name value"
	defaultLocale = "Default Locale value"
	brandingOptions = "includeCompanyLogo"
	roleScopeTagIds = @(
	"Role Scope Tag Ids value"
)
}

New-MgDeviceManagementNotificationMessageTemplate -BodyParameter $params

```
This example shows how to use the New-MgDeviceManagementNotificationMessageTemplate Cmdlet.

