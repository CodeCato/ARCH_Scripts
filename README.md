# ARCH_Scripts
Shell scripts I wrote to add functionality to a minimal window manager setup, such as i3.

---

### Basic usage
These scripts are to be put in the **~/exe/** folder.
All scripts can be called without needing to add all subfolders to $PATH. The executer script **"_ex"** sits at the top of the directory tree, which lets you call any scrtip from any subfolder. The symbolic links present in the folder point to scripts in the **"operators"** folder. These can be used to add/delete scripts, add/delete markdown based notes and view all present scripts.

### Available scripts *(output of ~/exe/_lS | ~/exe/operators/_listScripts)*
```
 ____            _       _       
/ ___|  ___ _ __(_)_ __ | |_ ___ 
\___ \ / __| '__| | '_ \| __/ __|
 ___) | (__| |  | | |_) | |_\__ \
|____/ \___|_|  |_| .__/ \__|___/
                  |_|            
###Operator Scripts###
[exe]
┌─ _vN
├─ _dS
├─ _cN
├─ _aN
├─ _aS
└─ _lS

###User Scripts###
[exe]
└─ 
--[notifications]
--┌─ notificationBar
--└─ i3exitSessionDiag
--[startup]
--┌─ addExePath
--├─ launchPolybar
--├─ i3startup
--├─ launchDunst
--├─ launchCompositor
--├─ launchTilda
--└─ launchKdeconnect
--[applications]
--┌─ tabbedSurf
--├─ womic
--└─ UnityHub
--[hardware_access]
--┌─ adjustBrightness
--├─ adjustVolume
--└─ lockSession
--[filesystem]
--┌─ extract
--└─ lfetch
--[img]
--┌─ rotImg
--├─ applyWallpaper
--└─ setWallpaper
--[dmenu]
--┌─ mMount
--├─ mScreenshot
--├─ mEmoji
--├─ mDisplays
--├─ mKbLayout
--└─ mDoom
```
