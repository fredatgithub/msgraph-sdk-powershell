### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Beta.Security

$params = @{
	"@odata.type" = "#microsoft.graph.security.departmentTemplate"
	displayName = "Finance"
}

New-MgBetaSecurityLabelDepartment -BodyParameter $params

```
This example shows how to use the New-MgBetaSecurityLabelDepartment Cmdlet.

