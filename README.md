# ZSH Configuration 🚀

This repository contains a well-structured Zsh configuration that enhances shell usability, provides aesthetic customizations, and optimizes command-line efficiency. Below are the key features and configurations included in this setup.

## Features ✨
- **Custom Prompt 🖥️**: Displays username, directory, and Git branch status with icons.
- **Syntax Highlighting 🎨**: Enhances readability of commands.
- **Autosuggestions 🤖**: Suggests previously used commands as you type.
- **History Management 📜**: Avoids duplicate entries and improves command recall.
- **Completion Enhancements ⚡**: Improves Zsh completion with colors and smart matching.
- **Aliases & Functions 🛠️**: Includes useful aliases and a custom directory icon function.
- **Custom Keybindings ⌨️**: Improves navigation and command history search.
- **Theming & UI Improvements 🎭**: Uses color schemes and symbols for a visually appealing terminal experience.

## Environment Variables 🌍
- `EDITOR`: Set to `geany` 📝.
- `BROWSER`: Set to `firefox` 🌐.
- `HISTORY_IGNORE`: Ignores common commands from history ⏳.
- `SUDO_PROMPT`: Custom sudo prompt for a personalized touch 🔐.
- `BAT_THEME`: Uses `base16` for syntax highlighting 🌈.

## Path Customization 🛤️
The script ensures that `~/.local/bin` is added to `PATH` if it exists 🏗️.

## Completion System ✅
- Loads Zsh completion system and caches it for faster performance 🚀.
- Uses verbose and color-enhanced completion 🎨.
- Enables smart pattern matching for more intuitive completion 🧠.

## Custom Keybindings ⌨️
- Tab completion enhanced with a red dot indicator 🔴.
- History search with up/down arrows 🔼🔽.

## Command History Configuration 🕰️
- Stores up to 5000 entries 📜.
- Shares history between sessions 🔄.
- Removes duplicate commands from history 🚫.

## Terminal Behavior Tweaks 🖥️
- `AUTOCD`: Allows changing directories by typing their names 📂.
- `MENU_COMPLETE`: Enables selection-based auto-completion 🖱️.
- `COMPLETE_IN_WORD`: Supports mid-word completion ✍️.

## Prompt Customization 🎨
The prompt includes:
- **OS Icon 🏴**: Displays Arch Linux logo.
- **Username 👤**: Styled with magenta color.
- **Directory Icon 📁**: Home (``) or folder (``).
- **Current Directory 📌**: Shown in red.
- **Git Branch Status 🌿**: Displays branch name with ``.
- **Success/Failure Indicators ✅❌**: `` in green (success) or red (failure).

## Custom Functions ⚙️
### `dir_icon()` 🗂️
Displays an icon based on the current directory:
- `` for home 🏠
- `` for other directories 📂

### `command_not_found_handler()` ❓
Prints a custom error message when an unrecognized command is entered 🚫.

### `cd()` 📂
Enhances the `cd` command:
- Prints a welcome message for each directory change 💬.
- Reminds the user to stay hydrated 💧.

## Fun Features 🎉
- Random compliments on shell startup 😍.
- Custom animated shutdown alias 🔄.

## Plugins Used 🔌
- **Zsh Autosuggestions 🤖**: Suggests previously used commands.
- **Zsh Syntax Highlighting 🎨**: Highlights commands for better readability.
- **Zsh History Substring Search 🔍**: Allows searching command history by substrings.

## Keybindings ⌨️
- `Up/Down Arrow` 🔼🔽: Search history based on substring input.
- `Del Key` ⌫: Deletes characters correctly.

## Installation 🛠️
1. Clone this repository 📂.
2. Copy the `.zshrc` file to `~/.zshrc` 📜.
3. Ensure required plugins are installed 📦.
4. Restart your terminal or run `source ~/.zshrc` 🔄.

## Contributing 🤝
Feel free to fork and customize this setup according to your needs. Pull requests are welcome! 🚀

