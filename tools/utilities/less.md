# [LESS](https://man7.org/linux/man-pages/man1/less.1.html)
`Less` is a command line utility that displays the contents of a file or a command output, one page at a time (both forward and backward)

__Open__ a file
```
less [OPTIONS] filename
```

- `E` - Exit when EOF
- `N` - Display line numbers
- `X` - Display output without clearing the screen on exit
- `p` - Start at the first occurrence of "pattern" in the file

__Redirect__ some output to less
```
ps aux | less
```

---
## Keyboard Navigation

- `Up / down arrow keys and k / j` - Move up / down one line.
- `right - left arrow key` - Scroll horizontally
- `spacebar` - Move down one page
- `b` - Move up one page.
- `g / G` - Go to the first / last line.
- `Ng` - Go to the Nth line
- `/search` - Search forward from the current position for the "search"
- `?search` - Search backward from the current position for the "search"
- `n / N` - When searching, go to the next / previous occurrence
- `q` - Quit less
