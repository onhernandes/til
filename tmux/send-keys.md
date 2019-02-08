# Send commands to another tmux session

---

You can send commands to another tmux session using `send-keys` command from tmux

```
tmux send-keys -t "<session-name>:<window-index>.<pane-index>" C-z 'ls /var/www -l' Enter
```
