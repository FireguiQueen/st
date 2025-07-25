# ST: Simple Terminal
ST is a simple terminal emulator for X11 which sucks less. 

## Why ST
Clean. Lightweight. Not bloated. Low RAM usage (3-5MB). And fully customizable to look just as good as any other terminal emulator.

### Note
This is a fork of st. For the official source, please visit: https://st.suckless.org/

---

## Applied patches
- [Scrollback](https://st.suckless.org/patches/scrollback/)
- [Alpha](https://st.suckless.org/patches/alpha/)
- [Column redraw](https://st.suckless.org/patches/columnredraw/)
  

---
## Dependencies
- **Font:** hack nerd font. [download here](https://www.nerdfonts.com/font-downloads)
- **Window compositor:** [Picom](https://github.com/yshui/picom) (recommended).

---

## Key binds
This build uses Vim-style key binds. If you're not familiar yet, you can get used to them by playing [Vim Adventures](https://vim-adventures.com/) in your browser.
| Action                  | Default Keybind  |
| :---------------------  | :--------------- |
| Scroll one line up      | `Ctrl + k`       |
| Scroll one line down    | `Ctrl + j`       |
| Scroll half page up     | `Ctrl + u`       |
| Scroll half page down   | `Ctrl + d`       |


## Installation
``` 
git clone https://github.com/FireguiQueen/st.git
cd st
sudo make clean install
``` 
