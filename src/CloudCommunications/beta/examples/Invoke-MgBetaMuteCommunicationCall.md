### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Beta.CloudCommunications

$params = @{
	clientContext = "clientContext-value"
}

Invoke-MgBetaMuteCommunicationCall -CallId $callId -BodyParameter $params

```
This example shows how to use the Invoke-MgBetaMuteCommunicationCall Cmdlet.

