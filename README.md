# Dotfiles

This repository contains my personal configuration files (dotfiles) for various tools and applications I use on Linux. The dotfiles are used to customize my terminal, editor, and other development tools, making it easy to set up and maintain a consistent development environment across multiple machines.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)

## Overview

The dotfiles in this repository are used to configure several development tools, including:
- Zsh for shell customization
- Vim for text editing
- Git for version control
- Various applications in the `.config/` directory

By keeping these files in version control, I can easily replicate my setup on new machines and share my configurations with others.

## Installation

To clone this repository and symlink the dotfiles to your home directory, follow these steps:

1. Change into your home directory:
   ```sh
   cd ~
   ```
2. Initialize a new Git repository:
   ```sh
   git init
   ```
3. Add a new remote for this repository:
   ```sh
   git remote add origin https://github.com/declanl2/dotfiles.git
   ```
4. Retrieve the contents of this repository:
   ```sh
   git reset --hard origin/master
   ```

## Usage

Once installed, the dotfiles will immediately apply their settings to your terminal, Git, Vim, and other tools.

