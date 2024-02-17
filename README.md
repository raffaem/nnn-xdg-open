# nnn-xdg-open

A nnn (=n³) plugin to open files with open of the applications that registered a .desktop file for that mimetype.

Inspects `/usr/share/applications` and `$HOME/.local/share/applications` to discover desktop files.

# Installation

1. Run `install.sh`.
2. Map to a keybinding by exporting
    ```
    NNN_PLUG='o:open;'
    ```

