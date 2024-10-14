# tmux

[tmux documentation](https://github.com/tmux/tmux/wiki)

## tmux layers

1. Session
2. Window
3. Pane

## shell commands

-   `tmux`: start tmux shell
-   `tmux new -s <session_name>`: start new tmux session called _session_name_ (`-s` for session)
-   `tmux ls`: list all tmux sessions
-   `tmux a`: attach to last session
-   `tmux a -t <id|session_name>`: attach to session by session _id_ or _name_ (`-t` for target)
-   `tmux kill-session`: kill current/last session
-   `tmux kill-session -t <id|session_name>`: kill session by session _id_ or _name_
-   `tmux kill-server`: kill all tmux sessions

## keymaps

-   `<C-b>`: prefix key

-   `<prefix><d>`: detach from session
-   `<prefix><%>`: split pane vertically (horizontal split)
-   `<prefix><">`: split pane horizontally (vertical split)
-   `<prefix><arrow_key>`: switch pane (to arrow direction)
-   `<prefix><q>`: show pane number (and switch to pane by number if the number is pressed while it's shown)
-   `<prefix><C-arrow_key>`: resize pane (to arrow direction)
-   `<prefix><Alt-arrow_key>`: resize pane (to arrow direction), bigger steps
-   `<prefix><Alt-1|2|3|4|5>`: pre-defined layout (1: even-horizontal, 2: even-vertical, 3: main-horizontal, 4: main-vertical, 5: tiled)
-   `<prefix><c>`: create new window
-   `<prefix><n>`: switch to next window
-   `<prefix><p>`: switch to previous window
-   `<prefix><0|1|2|3|4|5|6|7|8|9>`: switch to window by number
-   `<prefix><,>`: rename current window
-   `<prefix><w>`: list all windows and switch to window by number or moving with the arrows and pressing enter
-   `<prefix><x>`: kill pane, if from windows list kill selected window
-   `<prefix><&>`: kill window
-   `<prefix><:>`: command prompt

## command prompt

-   `select-pane -t <id|idx>` : select pane by _id_ or _idx_
