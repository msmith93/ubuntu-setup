# ubuntu-setup
Tracking the things I changed on my Ubuntu setup

## MacOS keyboard shortcuts
~https://github.com/petrstepanov/gnome-macos-remap~

Manually changed a few shortcuts:
* Install gnome tweaks
  * sudo apt install gnome-tweaks
  * Open Tweaks -> Keyboard and Mouse -> Additional Layout Options -> Alt and Win behavior -> Ctrl is mapped to Alt, Alt to Win
* Keyboard Settings (these must be done after the gnome tweak above so Super is mapper to Ctrl, etc)
  * Navigation
    * "Move to workspace on the left" <- Super+Left
    * "Move to workspace on the right" <- Super+Right
    * "Switch applications" <- Ctrl + Tab
    * "Switch windows" <- Alt + Tab
  * Launchers
    * "Search" <- Ctrl + Space
* bashrc
  * Add the following line:
    ```
    # Make Ctrl+K interrupt command in terminal
    stty intr \^k
    ```

## View HEIC images
https://askubuntu.com/a/1099378

