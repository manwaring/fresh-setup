# WSL 2

### Install WSL 2

https://docs.microsoft.com/en-us/windows/wsl/install-win10

### Sometimes required dependency

https://docs.microsoft.com/en-us/windows/wsl/wsl2-kernel

### Install Ubuntu LTS

https://www.microsoft.com/en-us/p/ubuntu-2004-lts/9n6svws3rx71?activetab=pivot:overviewtab

### Install Windows Terminal

https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab

### Add icon to Windows Terminal roaming

`%LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\RoamingState`

### Update Windows Terminal settings

```json
{
  "guid": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",
  "hidden": false,
  "name": "Ubuntu-20.04",
  "source": "Windows.Terminal.Wsl",
  "icon": "ms-appdata:///roaming/ubuntu.webp"
},
```
