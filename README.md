# dotfiles

This repository houses the collection of my personal dotfiles. I have
separate repositories for each of my respective dotfile collections for
each application. This repo holds references to them and an installation
script to install all of them appropriately. I prefer this setup because
the history of each of the dotfiles are scoped to their respective area,
`vim` in `dotvim`, `zsh` in `dotzsh`, etc.

## List of Dotfiles

The following is a list of applications and their various dotfile
repositories that this references and installs. Each linked repositories
has detailed documentation on each of dot file collections.

- [zsh](http://github.com/cyphactor/dotzsh)
- [tmux](http://github.com/cyphactor/dottmux)
- [vim](http://github.com/cyphactor/dotvim)
- [neovim](http://github.com/cyphactor/dotnvim)
- [git](http://github.com/cyphactor/dotgit)
- [ack](http://github.com/cyphactor/dotack)

## Usage

Below are details on how to use the provided scripts.

### Clone dotfiles

First you need to clone the dotfiles to your workspace. I do this by
doing the following:

```shell
git clone git@github.com:cyphactor/dotfiles.git ~/code/personal/dotfiles
```

Once you have cloned the repository you can use the provided scripts to
perform any of the following actions.

### Install dotfiles

You can install the dotfiles by running the following in your shell,
assuming of course that you are currently in the `dotfiles` directory.

```shell
./install
```

## Contributing

1. Fork it ([https://github.com/cyphactor/dotfiles/fork](https://github.com/cyphactor/dotfiles/fork))
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
