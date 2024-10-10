# tmux layers

1. Session
2. Window
3. Pane

# shell commands

-   `tmux`: start tmux shell
-   `tmux new -s <session_name>`: start new tmux session called _session_name_ (`-s` for session)
-   `tmux ls`: list all tmux sessions
-   `tmux a`: attach to last session
-   `tmux a -t <id|session_name>`: attach to session by session _id_ or _name_ (`-t` for target)
-   `tmux kill-session`: kill current/last session
-   `tmux kill-session -t <id|session_name>`: kill session by session _id_ or _name_
-   `tmux kill-server`: kill all tmux sessions

# keymaps

-   `<C-b>`: prefix key

-   `<C-b><d>`: detach from session
-   `<C-b><%>`: split pane vertically (horizontal split)
-   `<C-b><">`: split pane horizontally (vertical split)
-   `<C-b><arrow_key>`: switch pane (to arrow direction)
-   `<C-b><q>`: show pane number (and switch to pane by number if the number is pressed while it's shown)
-   `<C-b><C-arrow_key>`: resize pane (to arrow direction)
-   `<C-b><Alt-arrow_key>`: resize pane (to arrow direction), bigger steps
-   `<C-b><Alt-1|2|3|4|5>`: pre-defined layout (1: even-horizontal, 2: even-vertical, 3: main-horizontal, 4: main-vertical, 5: tiled)
-   `<C-b><c>`: create new window
-   `<C-b><n>`: switch to next window
-   `<C-b><p>`: switch to previous window
-   `<C-b><0|1|2|3|4|5|6|7|8|9>`: switch to window by number
-   `<C-b><,>`: rename current window
-   `<C-b><w>`: list all windows and switch to window by number or moving with the arrows and pressing enter
-   `<C-b><x>`: kill pane, if from windows list kill selected window
-   `<C-b><&>`: kill window
