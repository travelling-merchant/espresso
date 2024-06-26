# espresso
horrible, horrific, bill gates os dotfiles

## Software to install

windows sucks at the end I still had to install a lot of 
visual studio developing kits to get all other things to work,
pay special attention to all the c++ dev kits

### scoop package manager

to install the scoop package manager visit scoop.sh or use following command.

```shell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

### Software with scoop

```shell
scoop bucket add main
scoop bucket add extras
scoop bucket add versions
scoop bucket add nerd-fonts
scoop bucket add nonportable

scoop install versions/firefox-developer
scoop install main/vim
scoop install main/neovim
scoop install extras/obsidian
scoop install main/starship
scoop install extras/komorebi
scoop install extras/whkd
scoop install versions/mingw-winlibs-llvm
scoop install nerd-fonts/Lekton-NF
scoop install extras/onefetch
scoop install extras/draw.io
scoop install main/fastfetch
scoop install main/cpufetch
scoop install nonportable/sql-server-management-studio-np
```

```shell
mkdir ~\Documents\WindowsPowerShell
mkdir ~\.config\fastfetch
//fastfetch --gen-config
```

```cmd
mklink "%UserProfile%\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1" "%UserProfile%\espresso\shell\Microsoft.PowerShell_profile.ps1"
mklink "%UserProfile%\.config\fastfetch\fastfetch.jsonc" "%UserProfile%\espresso\fastfetch\fastfetch.jsonc"
```

