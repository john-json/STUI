

# STUI - Start menu for your terminal.



# info
Python based start screen for your terminal. 
clock, weather and minimal system Info.

# Screenshots
![stui_menu](https://raw.githubusercontent.com/john-json/customenu-cli/refs/heads/main/Screenshot.png)

![sub_menu](https://raw.githubusercontent.com/john-json/customenu-cli/refs/heads/main/Screenshot_submenu.png)



# Apps to install for best experience:
System info: https://github.com/Macchina-CLI/macchina
</br>
Spotify: https://github.com/aome510/spotify-player
</br>
Search: https://github.com/junegunn/fzf
</br>
Editor: https://neovim.io/doc/install/
</br>
Matrix: https://github.com/abishekvashok/cmatrix
</br>
Finder: https://github.com/sxyazi/yazi
</br>
config is set to use .zshrc https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH
</br>
</br>

# Customise Header & Menu names
Use header.txt to change the header used with ascii & use menu.json to change the menu names.
</br>

# To run

```
python /path/to/menufolder/startmenu.py
```
or add to zshrc to run with "menu" command

```
alias menu="python3 ~/.config/customenu-cli/startmenu.py"
```

# To use as a startmenu in zsh add this line

```
if [ -z "$GHOSTTY_MENU_SHOWN" ]; then </br>
    export GHOSTTY_MENU_SHOWN=1</br>
    ~/.config/customenu-cli/startmenu.py</br>
fi
```
