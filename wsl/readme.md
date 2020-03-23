
# Installing #

```powershell
# run as Admin
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux

Invoke-WebRequest -Uri https://aka.ms/wsl-ubuntu-1804 -OutFile Ubuntu.appx -UseBasicParsing

Add-AppxPackage .\Ubuntu.appx
```

## Reference ##

- https://docs.microsoft.com/en-us/windows/wsl/install-win10
- https://docs.microsoft.com/en-us/windows/wsl/install-manual
- https://docs.microsoft.com/en-us/windows/wsl/initialize-distro
- https://docs.microsoft.com/en-us/windows/wsl/about
