# dotfiles plugin for the asdf version manager

## Dependencies

- `bash`, `curl`, `tar`.

## Install
### Plugin

```shell
asdf plugin add dotfiles https://github.com/juli3nk/asdf-dotfiles.git
```

### dotfiles

```shell
# Show all installable versions
asdf list-all dotfiles

# Install specific version
asdf install dotfiles latest

# Set a version globally (on your ~/.tool-versions file)
asdf global dotfiles latest

# Now dotfiles commands are available
dotfiles -version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.
