### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Files

$params = @{
	recipients = @(
		@{
			email = "ryan@contoso.com"
		}
	)
	message = "Here's the file that we're collaborating on."
	requireSignIn = $true
	sendInvitation = $true
	roles = @(
	"write"
)
password = "password123"
expirationDateTime = "2018-07-15T14:00:00.000Z"
}

Invoke-MgInviteDriveItem -DriveId $driveId -DriveItemId $driveItemId -BodyParameter $params

```
This example shows how to use the Invoke-MgInviteDriveItem Cmdlet.

