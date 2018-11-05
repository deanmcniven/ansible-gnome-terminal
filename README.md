# gnome-terminal

Ansible role to configure gnome-terminal

Sets up:
* Gnome-terminal to launch into tmux
* Colour theme and window style

## Optional Config
The following variables default to true. Set them to false to switch off the indicated functionality.
* `gnome_terminal_hide_menubar`: Hides the gnome-terminal menubar
* `gnome_terminal_hide_scrollbars`: Hides the gnome-terminal scrollbars
* `gnome_terminal_set_colour_theme`: Changes the colour palette
* `gnome_terminal_start_in_tmux`: Runs tmux on launch of gnome-terminal
* `gnome_terminal_set_unlimited_scrollback`: Enables unlimited scrollback

