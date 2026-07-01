# Keyd Configuration

`keyd` is a Linux keyboard remapping daemon that remaps keys at the **kernel input level**. It allows you to customize the behavior of individual keyboards using their device IDs.

For more information, visit the official Keyd GitHub repository.

## Configuration Location

```text
/etc/keyd
```

## Important Notes

- Editing files in `/etc/keyd` requires **root privileges**, so use `sudo`.
- Reload or restart `keyd` after making any configuration changes.

## Useful Commands

### Reload the configuration

```bash
sudo keyd reload
```

### Restart the Keyd service

```bash
sudo systemctl restart keyd
```

### Stop the Keyd service

```bash
sudo systemctl stop keyd
```
