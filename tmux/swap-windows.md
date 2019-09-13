# Send commands to another tmux session

---

Swap windows on tmux from within prompt

Access prompt with `<Prefix>:`

```
swap-window -s 1 -t 5
```

to let window number 1 and window number 5 swap their positions.

To swap the current window with the top window, do:

```
swap-window -t 0
```
