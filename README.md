Write-Host "Starting Security Audit..."

.\scripts\firewall_check.ps1
.\scripts\defender_check.ps1
.\scripts\user_check.ps1
.\scripts\password_policy_check.ps1

Write-Host "Audit Complete."
