# Tmux Sessionizer

This folder contains the `tmux-sessionizer` script and its configuration file.

## File Locations

| File | Install Location |
|------|------------------|
| `tmux-sessionizer` | `~/.local/bin/tmux-sessionizer` |
| `tmux-sessionizer.conf` | `~/.config/tmux-sessionizer/tmux-sessionizer.conf` |

## Installation

Create the required directories:

```bash
mkdir -p ~/.local/bin
mkdir -p ~/.config/tmux-sessionizer
```

Copy the files to their respective locations:

```bash
cp tmux-sessionizer ~/.local/bin/
cp tmux-sessionizer.conf ~/.config/tmux-sessionizer/
```

Make the script executable:

```bash
chmod +x ~/.local/bin/tmux-sessionizer
```

## Verify Installation

```bash
which tmux-sessionizer
```

Expected output:

```text
/home/<username>/.local/bin/tmux-sessionizer
```
