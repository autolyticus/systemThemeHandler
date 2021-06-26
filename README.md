# systemThemeHandler

A simple script that detects changes in the system theme mode (dark mode) and runs additional scripts when it does.

Works for MacOS, Windows and Linux.

## Installation
1. Add the script to your path (I use `$HOME/.local/bin`)
2. After that, add the script to your shell's prompt command.
I use Fish, so following the documentation for [Fish Event Handlers](https://fishshell.com/docs/current/index.html#event), create an additional file _systemThemeHandler.fish in your conf.d directory (Default location: ~/.config/fish/conf.d)

That's it! Now changes to the system theme will be detected when you reload your shell.

