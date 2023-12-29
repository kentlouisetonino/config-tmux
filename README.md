## Description
> - This repository includes the `Tmux` (Terminal Multiplexer) guides and config.

<br />
<br />



### Configuration Setup
> - Clone this repository.

```bash
git clone git@github.com:kentlouisetonino/config-tmux.git
```

> - Copy the tmux config to the `~` directory.

```bash
# Go first to the cloned directory.
cd config-tmux

# Copy the file in home directory.
cp .tmux.conf ~/.tmux.conf
```

> - Load the tmux config and execute the configuration file.

```bash
tmux source ~/.tmux.conf
```

> - Restart the terminal.

<br />
<br />



### Commands
```bash
# Kill all the session and exit the app. 
tmux kill-server
```

```plaintext
Ctrl-b + %              : Split pane vertically.
Ctrl-b + "              : Split pane horizontally.
Ctrl-b + Left Arrow     : Move to the left pane.
Ctrl-b + Right Arrow    : Move to the right pane.
Ctrl-b + Up Arrow       : Move to the top pane.
Ctrl-b + Down Arrow     : Move to the down pane.
Ctrl-b + ;              : Switch to last active pane.
Ctrl-b + o              : Switch to next pane. This will switch the arrangement of pane.
```

