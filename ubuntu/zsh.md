# Settings

## ZSH and Oh My ZSH

1) `sudo apt-get install zsh`

2) `sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

3) Make zsh the default by `sudo nano ~/.bashrc` then adding `exec zsh` in the end of the file 

## Fonts

1) `sudo apt-get install powerline fonts-powerline`

## Theme Terminal

1) Install [powerlevel10k](https://github.com/romkatv/powerlevel10k#extremely-customizable)

2) Use font `MesloLGS NF` 

3) Terminal setting:
 - Background: #111420
 - Theme: XTerm (but change blue for #1B80C4)

4) On VSCode add in preferences: `"terminal.integrated.fontFamily": "MesloLGS NF"`. Restart VS Code for it to work.

5) On VSCode use: 
```
"workbench.colorCustomizations": {
  "terminal.ansiBlue":"#0066FF"
}
```
