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

### Activate
```
irm https://get.activated.win | iex
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
- File Explorer
  - Show Hidden files
  - Show file extensions
- Adjust Sleep Settings

### Page File
- Advanced System Settings
- Performance Options > Advanced > VMemory > Change
- Custom Size: 40000  (40GB)

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
- Setup Start up scripts
  - Win + R -> shell:startup
  - Copy ahk file
  - "Paste Shortcut"

### AutoLogin
- Settings > Account > Sign In Options > Required to sign when been away no
- Regedit
  - `Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\PasswordLess\Device`
  - `DevicePasswordLessBuildVersion` = 0
- netplwiz
  - Untick "Users must enter password...."
  - username is full email

### Software
- Chrome
- VSCode
    - Vim
    - Theme

#### Games
- Steam
  - Move game install folder to root dir
    - https://github.com/LostDragonist/steam-library-setup-tool/releases
    - EXIT Steam
    - like: `C://SteamLibrary`
    - Rename old library to "DONT USE"
    - Make New Library Default

- Discord
- Boot XBOX app to update and login
- Launch game bar and turn off open with controller guide
- Xbox Accessories app for controllers https://apps.microsoft.com/detail/9nblggh30xj3?hl=en-US&gl=US



### Docker / WSL
- TODO


### Disable StartUp 
- shift-ctrl-esc
- Toggle off most startup services.
