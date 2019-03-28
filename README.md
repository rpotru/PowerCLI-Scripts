# PowerCLI-Scripts
# useful commands for day to day VMware administration

# Remove any mounted ISO's to VM and set to Client Device.
Get-VM | Get-CDDrive | Where {$_.ISOPath -ne $null} | Set-CDDrive -NoMedia -Confirm:$false






