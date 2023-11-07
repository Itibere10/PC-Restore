# PC-Restore

## Chocolatey automatic install
Download programs used in the PC with Chocolatey Package manager for Windows.

Before execute the file ***choco-install.bat***, you need to install **Chocolatey**.
Run this command on ***PowerShell*** as ***Administrator*** to install it:

```Batchfile
  Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
## Manual software install
Use this commands to open the essencial software to the atual PC Drivers:
> NVidia Drivers (To use with games, EasyAntiCheat,optimization, etc)
> Printer Driver (HP Deskjet 2400 Series)

```Batchfile
  start https://printerdrivers.com/hp-deskjet-d2466-driver/ & start https://www.nvidia.com/pt-br/geforce/drivers/
```
