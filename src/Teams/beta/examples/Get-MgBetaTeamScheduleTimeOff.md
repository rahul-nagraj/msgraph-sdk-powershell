### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Beta.Teams

Get-MgBetaTeamScheduleTimeOff -TeamId $teamId -Filter "sharedTimeOff/startDateTime ge 2019-03-11T00:00:00.000Z and sharedTimeOff/endDateTime le 2019-03-18T00:00:00.000Z and draftTimeOff/startDateTime ge 2019-03-11T00:00:00.000Z and draftTimeOff/endDateTime le 2019-03-18T00:00:00.000Z" 

```
This example shows how to use the Get-MgBetaTeamScheduleTimeOff Cmdlet.

