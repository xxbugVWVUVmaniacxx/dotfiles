## Configs

### Starship prompt

1. Install a [NerdFont](https://www.nerdfonts.com/font-downloads). I use IosevkaTerm.
2. Install [Starship](https://starship.rs/)(MacOS): `curl -sS https://starship.rs/install.sh | sh` (brew, too)
3. Add to end of .zshrc: `eval "$(starship init zsh)"`
4. Put a copy of starship_cp.toml in `~/.config` and rename it **starship.toml**
5. Run `source ~/.zshrc` from your terminal.

### iTerm2 terminal
general theme is 
- solarized dark, 
- Appearance > General > Theme > Minimal
- persistent tabs
#### Install
After pulling this repo:

> *Iterm2 > Settings > Profiles > Other Actions > Import JSON Profiles...*

### ~/.zshrc
- aliases
- functions
- init configurations
