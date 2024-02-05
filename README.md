# dotfiles

Welcome to my dotfiles.
This is a collection of my personal dotfiles for my development environment.
It includes my vim, tmux, and zsh configurations.
Feel free to use them as a reference or copy them for your own use.

This config is designed to work on both Unix-like and Windows systems.
I don't always run on all the different platforms, so it may be broken on some systems.
If that's the case, feel free to open an issue or submit a pull request.

Here is a list of some of the features of this configuration:

- Neovim configuration using [my config](https://github.com/BSFishy/init.lua)
  - Based on LazyVim
  - Gruvbox theme with rainbow delimeters
- Tmux configuration
  - Simple, mostly to make it work well with Neovim
- Zsh configuration
  - Includes installing Oh-My-Zsh
  - Adds a [.commonrc](dot_commonrc.tmpl) for both Zsh and Bash
  - Includes a [Starship](https://starship.rs/) configuration
- Installs latest JetBrains Mono Nerd Font
- Wezterm configuration

## Requirements

First, you will need to install chezmoi.
Information on how to do so can be found [here](https://www.chezmoi.io/install/).

There are also a few other dependencies that are required for the configurations to work properly.

- Git
- Zsh if you're on a Unix-like system

## Installation

To install:

```sh
chezmoi init https://github.com/BSFishy/dotfiles.git
```

To update to the latest version:

```sh
chezmoi update
```
