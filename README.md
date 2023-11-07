# PC-Restore

## Chocolatey automatic install
Download programs used in the PC with Chocolatey Package manager for Windows.

Before execute the file ***choco command line string***, you need to install **Chocolatey**.
Run this command on ***PowerShell*** as ***Administrator*** to install it:

```Batchfile
  Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

With Chocolatey installed, run this command:
```Batchfile
  choco install microsoft-windows-terminal steam epicgameslauncher discord spotify git vscode python orwelldevcpp winrar -r -y
```

## Manual software install
Use this commands to open the essencial software to the atual PC Drivers:
* NVIDIA GeForce Drivers (To use with games, EasyAntiCheat,optimization, etc)
* Printer Driver (HP Deskjet 2400 Series)

```Batchfile
  start https://printerdrivers.com/hp-deskjet-d2466-driver/ & start https://www.nvidia.com/pt-br/geforce/drivers/ & start https://apps.microsoft.com/detail/windows-terminal/9N0DX20HK701?hl=pt-br&gl=US
```
