# Punchy Cyberpunk Theme

Inspiration: https://github.com/prometheux-ar/cyberpunk

## Installation

### Vim

Copy the file in the colors directory to `.vim/colors` or
`~/.config/nvim/colors` and add this to your `.vimrc`

```vimscript
set termguicolors
colorscheme cyberpunk
```

### emacs

Copy `emacs/cyberpunk-theme.el` to a directory listed in `custom-theme-load-path`
(by default it is `~/.emacs.d`) and put this in your `init.el`

```
(load-theme 'cyberpunk t)
```

## Screenshots

![vim](./screenshots/cyberpunk.png)
![emacs](./screenshots/cyberpunk-emacs.png)
