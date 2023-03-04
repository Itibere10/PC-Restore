# PC-Restore
Download programs used in the PC with Chocolatey Package manager for Windows.

Before execute the file ***choco-install.bat***, you need to install **Chocolatey**.
Run this command on ***PowerShell*** as ***Administrator*** to install it:

```Batchfile
  Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
