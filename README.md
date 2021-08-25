# zsh-custom

## Customized af-magic theme
Compact version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Changes:
* Dashed horizontal delimiter was replaced with a blank line as it causes a mess on the terminal size decrease.
* Prompt moved to a new line to stick it on the left side.
* Minor cosmetics changes.

![screenshot](/screenshot.png?raw=true)

## Installation

### Antigen

Add to `.zshrc` before `antigen apply`:

    antigen bundle lorond/zsh-custom themes/af-magic-lorond.zsh-theme
    antigen theme af-magic-lorond
