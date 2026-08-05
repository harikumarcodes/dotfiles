# Dotfiles
Linux configuration files managed with GNU Stow.

## Usage

### Apply a config:
```bash
cd ~/dotfiles
stow helix
```

### Remove a config:
```bash
stow -D helix
```

## Notes

### You can preview changes before applying:
```bash
stow -n -v helix
```
