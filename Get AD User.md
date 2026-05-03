```powershell
# This is a PowerShell comment
Get-Service | Where-Object { $_.Status -eq 'Running' }
```
