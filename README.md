## Description
> - This repository includes the `Tmux` (Terminal Multiplexer) guides and config.

<br />
<br />



### Configuration Setup

```bash
# Go to the root directory.
cd ~

# Create a config file.
touch .tmux.conf
```

> - Inside the `.tmux.conf` file insert the bindings.

```bash
# New panes in current directory.
bind c new-window -c "#{pane_current_path}"
bind '"' split-window -c "#{pane_current_path}"
bind % split-window -h -c "#{pane_current_path}"
```

> - Save the file and load the the configuration file.

```bash
tmux source ~/.tmux.conf
```

> - Restart the terminal

<br />
<br />



### Commands

```plaintext
Ctrl-b + %              : Split vertically.
Ctrl-b + "              : Spit horizontally.
Ctrl-b + Left Arrow     : Move to the left pane.
Ctrl-b + Right Arrow    : Move to the right pane.
```

