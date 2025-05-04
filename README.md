### GIT
- Download Git
  - In setup, make sure to toggle clrf line ending stuff
- Setup SSH Keys
```
ssh-keygen -t ed25519 -C "travis@oldmanz.com"
cat ..\.ssh\id_ed25519.pub
```
- Add key to Github
- Clone this repo
```
git clone git@github.com:oldmanz/windows.git
```
- Set Git Settings
```
git config --global user.name oldmanz
git config --global user.email "travis@oldmanz.com"
```

### Graphics
- Download GPU Software (amd adren or nvidia)
- Set monitor and TV display settings

### Personalization
- Dark Theme
- Remove Recycle Bin
- Change Wallpaper
- Remove Icons from Dock
- Turn off Search
- Remove all apps from start menu

### Geek Uninstaller
- Download Geek Uninstaller

### Onedrive
- Uninstall Onedrive with Geek
- Edit Registry
```
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\User Shell Folders
```
  - Remove 'OneDrive' from all links
- Delete OneDrive Folder from home dir

### Shell
- Download Latest Powershell
```
winget install --id Microsoft.PowerShell --source winget
```
- Set as default in terminal
- Set Theme
- Can run in quake mode
    - win + ` when open

### Neovim
- Install
```
winget install --id=Neovim.Neovim  -e
```

### AHK
- Install AutoHotkey


### Other Software
- Chrome
- VSCode
    - Vim
    - Theme
- Steam
- Discord
- Cura
- Fusion 360
- Lightburn



### Docker / WSL
- TODO


### Disable StartUp 
- shift-ctrl-esc
- Toggle off most startup services.
