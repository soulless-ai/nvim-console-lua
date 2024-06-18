# Neovim Configuration

This repository contains a Neovim configuration using Lua for various plugins and settings.

## Prerequisites

- Neovim (version 0.5 or higher)
- [Packer](https://github.com/wbthomason/packer.nvim) - Plugin manager for Neovim

## Installation

### 1. Install Neovim

Ensure that Neovim is installed on your system.

**For Ubuntu:**
```sh
sudo apt update
sudo apt install neovim
```

**For macOS (using Homebrew):**
```sh
brew install neovim
```

### 2. Install Packer
Install Packer, the plugin manager for Neovim, by running the following command:

```sh
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
  ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

### 3. Clone the Repository
Clone this repository to your Neovim configuration directory:

```sh
git clone https://github.com/soulless-ai/nvim-console-lua.git ~/.config/nvim
```

### 4. Install Plugins
Open Neovim and run the following command to install the plugins: ```  :PackerSync  ```

## Directory Structure
The configuration is organized as follows:

```sh
~/.config/nvim
├── init.lua
└── lua
    ├── core
    └── plugins
```

## Usage
After cloning the repository and running ```  :PackerSync  ```, you can start using Neovim with the configured plugins and settings.