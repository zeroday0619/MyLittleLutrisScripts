# Genshin Impact

### Description:
Play Genshin Impact on Linux.

### Technical notes:
- This script uses a patch that is not supported by MiHoYo, USE IT AT YOUR OWN RISK.
- You will need root rights to install this patch as it will modify /etc/hosts system file.
- You will need to find, edit, and run the patch manually - outside of Lutris - after the game update has finished.
- PATCH IS NOT APPLIED BY DEFAULT. To apply or revert it, right-click on the game icon/banner and select "execute script" --> https://imgur.com/D4jDdPX
- This script installer needs xdelta3, xterm, zenity binaries.
- If the install freezes during download, kill the "launcher.exe" process. Then launch the game from Lutris and choose option 2 in the menu "Update Genshin Impact". Once downloading and installing are completed, close the game, patch the game, start the game and choose option 1 in the menu.

# Genshin Impact - Update patch

### Description:
You already installed Genshin Impact with Lutris and just need to update your current install with latest patch.

### Technical notes:
Please follow this steps:
1) execute this script, it will install updated patch
2) update Geshin Impact to latest version (option 2) but do not launch it
3) apply new patch
To apply or revert patch, right-click on the game icon/banner and select "execute script" --> https://imgur.com/D4jDdPX

### Update notes:
1) unpatch current game (from lutris `execute script` for example)
2) run launcher and update the game
3) close launcher without run the game
4) download .zip of new pach from here
5) unzip this file on `WINE_PREFIX/drive_c/gi_patch/`
6) patch again (from lutris `execute script` for example)
7) run and play