# Ubuntu 18 Configs

## ZSH

Oh My Zsh

Clone this repository into $ZSH_CUSTOM/plugins (by default ~/.oh-my-zsh/custom/plugins)
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

Add the plugin to the list of plugins for Oh My Zsh to load (inside ~/.zshrc):
```
plugins=(zsh-autosuggestions)
```
Start a new terminal session.

** Manual (Git Clone)**
Clone this repository somewhere on your machine. This guide will assume ~/.zsh/zsh-autosuggestions.

```
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
```

Add the following to your .zshrc:
```
source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh
```
Start a new terminal session.


