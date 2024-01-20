# MaxConfig

A set of simple scripts and config files to get a linux environment looking pretty and functioning the way I like it.

# Prerequisites
- Zsh (as the default shell)
- Eza
- Thef__k

# How to Use
## Aliases and Prompt Enhancers
In your .zshrc file, add
```
export MAXCONFIG_DIR="<path_to_this_directory>"
source $MAXCONFIG_DIR/zsh/maxconfig.zsh
```

This will enable starship as well as thef__k in your prompt and add my aliases.

## Oh-My-Zsh
Run `zsh/oh-my-zsh-install.zsh`.

## Starship
Run `starship/starship-install.zsh`. Copy the `starship/starship.toml` to your `~/.config/` directory.

## KDE Theme
Add the `.colors` file in the `kde` folder to your KDE settings.