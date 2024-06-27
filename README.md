# ohmyzsh-theme-bsdpassion

## Introduction

A work in progress oh-my-zsh theme

Forked from https://github.com/ChesterYue/ohmyzsh-theme-passion

### Feature

* real time prompt
* command running time cost prompt
* command running error hint

## Usage

### Basic Zsh Theme

#### Install

1. clone repo
   ```
   git clone https://github.com/hulleyrob/ohmyzsh-theme-bsdpassion
   ```
2. copy theme
   ```
   cp ./ohmyzsh-theme-bsdpassion/bsdpassion.zsh-theme ~/.oh-my-zsh/themes/bsdpassion.zsh-theme
   ```
3. edit .zshrc change ZSH_THEME to 
    ```
   ZSH_THEME="bsdpassion"
    ```
11. execute zshrc
    ```
    source ~/.zshrc
    ```

* see also: [Overriding and adding themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Customization#overriding-and-adding-themes);

* plugins/zsh-interactive-cd is already sources in the .zshrc file

#### Recommended Zsh Plugins

1. [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
2. [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
3. [command-line fuzzy finder](https://github.com/junegunn/fzf)

#### iTerm2 Preferences

##### Color

<!-- cspell:disable-next-line -->
* iTerm2: settings -> Profiles -> Colors -> Color Presets -> import ```./bsdpassion.itermcolors``` ![color.png](./image/color.png)
* alternate terminal: try [Alternate terminal installation and configuration](https://iterm2colorschemes.com/)

##### Status Bar

* iTerm2: settings -> Appearance && settings -> Profiles -> Session -> Configure Status Bar ![status_0.png](./image/status_0.png) ![status_1.png](./image/status_1.png)

</details> <!-- markdownlint-disable-line -->

#### Why newline on the prompt?

<img width="871" alt="image" src="https://github.com/hulleyrob/ohmyzsh-theme-bsdpassion/assets/17217514/d314e37d-a1ba-4eb5-8897-2e9c342b94bf">

Useful if using smaller terminal windows

#### What do the red and green dot mean?

<img width="585" alt="image" src="https://github.com/hulleyrob/ohmyzsh-theme-bsdpassion/assets/17217514/3f42d544-e006-4830-b697-c4ffd3208f2b">

Red Dot   = Last command returned unsuccesful completion status

Green Dot = Last command returned succesful completion status
