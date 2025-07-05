# My Dotfiles

A collection of personal configuration files for various tools and environments.

## Overview

This repository contains my personal dotfiles, including:

- **Zsh Configuration**: Minimalist Zsh setup with Powerlevel10k.
- **Editor Settings**: Configuration for various text editors and IDEs.
- **Tool Configurations**: Settings for other command-line tools and applications.

## Zsh Configuration

### Overview

- Shell: [`Zsh`](https://github.com/zsh-users/zsh)
- Prompt: [`Powerlevel10k`](https://github.com/romkatv/powerlevel10k)
- Font: [`JetBrainsMono Nerd Font`](https://www.nerdfonts.com/font-downloads)

### Zsh Plugins

- [`git`](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git) — Git aliases and helpers (from Oh My Zsh, optional to replicate manually)
- [`zsh-autosuggestions`](https://github.com/zsh-users/zsh-autosuggestions) — Command autosuggestions
- [`zsh-syntax-highlighting`](https://github.com/zsh-users/zsh-syntax-highlighting) — Syntax highlighting for Zsh commands
- [`you-should-use`](https://github.com/MichaelAquilina/zsh-you-should-use) — Reminds you to use existing aliases

Clone each plugin into your preferred plugin directory and source them in `.zshrc`.

## General Configuration

### Files Included

- `.zshrc` — Main Zsh configuration
- `.p10k.zsh` — Powerlevel10k prompt configuration
- `.gemini/settings.json` — Gemini CLI specific settings.
