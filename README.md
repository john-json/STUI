

# STUI - Start menu for your terminal.


![alt text](https://raw.githubusercontent.com/john-json/customenu-cli/refs/heads/main/Screenshot.png)


# info

Python based.
</br>
need fuzzy finder to use the search.
</br>
yazi for the finder.

use header.txt to change the header text
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
