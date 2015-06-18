# SublimeScript - A Cinema 4D & Sublime Text plugin

*SublimeScript* is a plugin for Cinema 4D and Sublime Text that allows
you to sent code from Sublime Text to Cinema 4D and execute it as a script.

![Preview Image](preview.png)

## Installation

1. Download the latest code from GitHub and unpack the content into
your Cinema 4D plugin directory.

    ```
    Cinema 4D RXX/
        plugins/
            sublime-script/
                SublimeScriptServer.pyp
                sublime-plugin/
                    SublimeScriptSender/
                        ...
                ...
    ```

2. Copy (or symlink) the `SublimeScriptSender` folder to your sublime
package directory. You can open this directory by heading to Sublime
"Preferences > Browse Packages ...".

3. Start Cinema 4D and run the "Tools > Send Python Code" command from
Sublime! The default settings should work fine.

## Disclaimer

Note that having this plugin installed could make your computer
vulnerable to targeted attacks. Use only for development purpose and
do not use on production servers.
