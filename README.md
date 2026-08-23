

# STUI - Start menu for your terminal.


![alt text](https://raw.githubusercontent.com/john-json/customenu-cli/refs/heads/main/Screenshot.png)


# info

Python based.

# Apps needed:
Spotify: https://github.com/aome510/spotify-player
Search: https://github.com/junegunn/fzf
Editor: https://neovim.io/doc/install/
Matrix: https://github.com/abishekvashok/cmatrix
Finder: https://github.com/sxyazi/yazi
</br>
</br>
# Use header.txt to change the header text
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
