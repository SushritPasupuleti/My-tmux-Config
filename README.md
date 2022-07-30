# My tmux Config

All the things I'm using to make tmux work for me!

## Essentials

- [oh-my-tmux](https://github.com/gpakosz/.tmux) - Setup based on instructions from the repo. After following the guide, make sure to restart tmux (by killing the server with `kill-server`).

## Config

Install CLipboard integration for macOS

```bash
brew install reattach-to-user-namespace
```


```bash
# config is in ~/.tmux/.conf.local
# edit it with your editor of choice
# to sync with tmux config:
# from the folder where oh-my-tmux is installed
cp .tmux/.tmux.conf.local .
```

Additions to Config:

```conf

```

## Keybindings

**Prefix**: <kbd>CTRL</kbd> <kbd>a</kbd>

- *Prefix* <kbd>-</kbd> Horizontal Split

- *Prefix* <kbd>_ </kbd> Vertical Split

- *Prefix* <kbd>e</kbd> Edit Config

- *Prefix* <kbd>r</kbd> Reload Config

- *Prefix* <kbd>hjkl</kbd> Navigate Panes

- *Prefix* <kbd>x</kbd> Close Pane (Enter <kbd>y</kbd> to confirm close)

- *Prefix* <kbd>HJKL</kbd> Resize Panes

- *Prefix* <kbd><></kbd> Swap Pane Location

- *Prefix* <kbd>+</kbd> Maximize Pane into New Window

- *Prefix* <kbd>c</kbd> New Window

- *Prefix* <kbd>d</kbd> Detach Session

- *Prefix* <kbd>s</kbd> View all Windows in Current Session

- *Prefix* <kbd>0-9</kbd> Navigate Windows by Number

TPM:

- *Prefix* <kbd>I</kbd> Install Plugins

- *Prefix* <kbd>Alt</kbd> <kbd>u</kbd> Uninstall Plugins

- *Prefix* <kbd>u</kbd> Update Plugins

## Themes

Add to your config

```conf
# dracula theme
tmux_conf_theme_colour_0="default"    # background
tmux_conf_theme_colour_1="#282a36"    # background
tmux_conf_theme_colour_2="#303030"    # gray
tmux_conf_theme_colour_3="#f8f8f2"    # foreground
tmux_conf_theme_colour_4="#8be9fd"    # cyan
tmux_conf_theme_colour_5="#f1fa8c"    # yellow
tmux_conf_theme_colour_6="#282a36"    # background
tmux_conf_theme_colour_7="#f8f8f2"    # foreground
tmux_conf_theme_colour_8="#282a36"    # background
tmux_conf_theme_colour_9="#bd93f9"    # purple
tmux_conf_theme_colour_10="#6272a4"   # comment
tmux_conf_theme_colour_11="#50fa7b"   # green
tmux_conf_theme_colour_12="#f8f8f2"   # foreground
tmux_conf_theme_colour_13="#f8f8f2"   # foreground
tmux_conf_theme_colour_14="#282a36"   # background
tmux_conf_theme_colour_15="#44475a"   # selection
tmux_conf_theme_colour_16="#6272a4"   # comment
tmux_conf_theme_colour_17="#bd93f9"   # purple
tmux_conf_theme_colour_18="#ff5555"   # red
tmux_conf_theme_colour_19="#ffb86c"   # orange
tmux_conf_theme_colour_20="#ff79c6"   # pink

# monokai soda theme
tmux_conf_theme_colour_0="#1a1a1a"
tmux_conf_theme_colour_1="#282a36"
tmux_conf_theme_colour_2="#303030"
tmux_conf_theme_colour_3="#f6f6ef"
tmux_conf_theme_colour_4="#58d1eb"
tmux_conf_theme_colour_5="#ffb86c"
tmux_conf_theme_colour_6="#282a36"
tmux_conf_theme_colour_7="#f6f6ef"
tmux_conf_theme_colour_8="#282a36"
tmux_conf_theme_colour_9="#98e024"
tmux_conf_theme_colour_10="#9d65ff"
tmux_conf_theme_colour_11="#98e024"
tmux_conf_theme_colour_12="#f6f6ef"
tmux_conf_theme_colour_13="#f6f6ef"
tmux_conf_theme_colour_14="#282a36"
tmux_conf_theme_colour_15="#44475a"
tmux_conf_theme_colour_16="#9d65ff"
tmux_conf_theme_colour_17="#98e024"
tmux_conf_theme_colour_18="#f4005f"
tmux_conf_theme_colour_19="#ffb86c"
tmux_conf_theme_colour_20="#f4005f"

tmux_conf_theme_left_separator_main='\uE0B8'
tmux_conf_theme_left_separator_sub='\uE0B9'
tmux_conf_theme_right_separator_main='\uE0BA'
tmux_conf_theme_right_separator_sub='\uE0BB'
```

