# VI Editor – Fundamentals

The `vi` editor is a standard text editor available on virtually all Unix/Linux systems. It operates using modes, which is essential to understand before editing files.

---

## Modes

### Command Mode
- Default mode when opening `vi`
- Used for navigation and commands

### Insert Mode
- Used to write or modify text

### Switching Modes
- Command → Insert: press `i`
- Insert → Command: press `Esc`

---

## Navigation
- Arrow keys
- `h` (left) `j` (down) `k` (up) `l` (right)

---

## Editing Commands (Command Mode)
- `x` → delete character
- `dd` → delete entire line
- `yy` → copy line
- `p` → paste copied line

---

## Scrolling
- `Ctrl + u` → scroll up
- `Ctrl + d` → scroll down

---

## File Commands
Commands start with `:` (command-line mode)

- `:w` → save file
- `:w filename` → save with a name
- `:q` → quit
- `:q!` → quit without saving
- `:wq` → save and quit

---

## Search
- `/word` → search for a word
- `n` → go to next occurrence
