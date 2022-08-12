# .dotfiles

- install [GNU Stow](https://www.gnu.org/software/stow/)
	- mac: `brew install stow`
	- ubuntu: `apt install stow`

## setting up symlinks
- `cd ~/.dotfiles`
- `stow .`

## adding files
- `stow --dir=~/.dotfiles --target=~/`
