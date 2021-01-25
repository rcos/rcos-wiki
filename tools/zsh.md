# Zsh

**Website**: <https://www.zsh.org/>

Z shell (Zsh) is a Unix shell meant to be an extension on Bash. It is
highly extensible and configurable (including better auto completion,
auto correction, color customization, git integration, etc). Its extra
features and customization makes it highly regarded by \*nix
enthusiasts.

Apple announced that it will be adopted as the default shell for Mac OS
10.15 and beyond.

## Usage

It is used like any other shell. Do stuff by entering commands.

## Resources

#### Installation

[Here](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH) is
a guide for installing Zsh on various platforms. It ultimately boils
down to installing it from your package manager, and typing `zsh` in
your terminal to launch it. If you want to set Zsh as your default
shell, type `chsh -s $(which zsh)`.

#### Configuration

Like Bash, Zsh can be configured through
[dotfiles](https://wiki.archlinux.org/index.php/Dotfiles) (hidden \*nix
configuration files found in the home directory, whose names are
prefixed with a single `.`) such as `~/.zshrc`, `~/.zprofile`, etc. This
naming scheme is meant to mirror Bash\'s naming scheme `~/.bashrc`,
`~/.bash_profile`, `etc`. It can be extended further through frameworks
such as [oh my zsh](https://github.com/robbyrussell/oh-my-zsh) and
[prezto](https://github.com/sorin-ionescu/prezto). Color customization
can be achieved through standard [Xresources
customization](https://wiki.archlinux.org/index.php/X_resources) (mainly
for Linux terminals that are Xorg configurable, or through your
terminal\'s own configuration files.

#### Troubleshooting

Many Unix shell scripts online are written for Bash, as it is seen as
the \"old standard\". If you are having trouble running these scripts
while using Zsh, you can either switch over to Bash before running it by
typing `bash` in your terminal, or add a
[shebang](https://en.wikipedia.org/wiki/Shebang_(Unix))
`#!/usr/bin/env bash` at the very top of the script to have it
automatically run the script in bash.
