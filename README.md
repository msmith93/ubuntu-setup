# ubuntu-setup
Tracking the things I changed on my Ubuntu setup

## MacOS keyboard shortcuts
~https://github.com/petrstepanov/gnome-macos-remap~

Manually changed a few shortcuts:
* ~Install gnome tweaks~
  * sudo apt install gnome-tweaks
  * Open Tweaks -> Keyboard and Mouse -> Additional Layout Options -> Alt and Win behavior -> Ctrl is mapped to Alt, Alt to Win
* Keyboard Settings (these must be done after the gnome tweak above so Super is mapper to Ctrl, etc)
  * Navigation
    * "Move to workspace on the left" <- Ctrl+Left
    * "Move to workspace on the right" <- Ctrl+Right
    * "Switch applications" <- Alt + Tab
    * "Switch windows" <- Ctl + Tab
  * Launchers
    * "Search" <- Alt + Space
* Terminal Preferences
  * In Shortcuts, change anything that has "Shift + Ctrl + ?" to just "Alt + ?" 
* bashrc
  * ~Add the following line (because now Ctrl + C is for copy, not kill):~
    ```
    # Make Ctrl+K interrupt command in terminal
    stty intr \^k
    ```

## View HEIC images
https://askubuntu.com/a/1099378

```
sudo apt install heif-gdk-pixbuf heif-thumbnailer gimagereader gpicview
```
Now, open images with "Image Viewer" application instead of the default app. 

