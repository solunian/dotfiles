# dotfiles

For a nixos with hyprland setup, but files can be used piecemeal in other
systems.

## file placement

> assume all go in home directory (~) unless otherwise specified

- `~/.config/`: `hypr`, `kitty`, `mako`, `starship.toml`
- `/etc/nixos/`: `configuration.nix`
- `archived` are just old config files

## other notes

`.gitconfig` needs a gpg pub key for the signingkey value.

I should probably write a script to copy all the files into the git repo...
