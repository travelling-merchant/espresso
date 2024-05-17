# espresso
horrible, horrific, bill gates os dotfiles

## Software to install

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

scoop install main/vim
scoop install main/neovim
scoop install extras/obsidian
scoop install main/starship
scoop install extras/komorebi
scoop install extras/whkd
scoop install versions/mingw-winlibs-llvm
scoop install nerd-fonts/Hasklig-NF-Mono
```

```shell
mkdir ~\Documents\WindowsPowerShell
```

```cmd
mklink "%UserProfile%\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1" "%UserProfile%\espresso\shell\Microsoft.PowerShell_profile.ps1"
```
