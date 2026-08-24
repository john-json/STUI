

# STUI - Start menu for your terminal.


![alt text](https://raw.githubusercontent.com/john-json/customenu-cli/refs/heads/main/Screenshot.png)


# info

Python based.

# Apps needed:
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
# header
header.txt to change the header text
</br>

# To run

```
python /path/to/menufolder/startmenu.py
```

# To use as a startmenu in zsh add this line

```
if [ -z "$GHOSTTY_MENU_SHOWN" ]; then </br>
    export GHOSTTY_MENU_SHOWN=1</br>
    ~/.config/customenu-cli/startmenu.py</br>
fi
```
