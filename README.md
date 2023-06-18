<h1 align="center">Welcome to learn-vim-with-vscode 👋</h1>
<p>
This project aims to guide you through setting up and learning Vim within Visual Studio Code using the VSCodeVim and VSCode-Neovim extensions.
</p>

[![IT Man - Tip #38 - Learn Vim with VSCode [Vietnamese]](https://i.ytimg.com/vi/yTTPRm0ACl0/hqdefault.jpg)](https://www.youtube.com/watch?v=yTTPRm0ACl0)

## Setup

### VSCodeVim

VSCodeVim is a Vim emulator for Visual Studio Code.

1. Install the extension from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
2. After installation, you can modify settings in your settings.json file to customize the Vim experience. An example configuration can be found [here](https://github.com/VSCodeVim/Vim).

### VSCode-Neovim

VSCode-Neovim is an extension that integrates Neovim into Visual Studio Code for advanced Vim features.

1. Install Neovim on your system. The installation guide can be found [here](https://github.com/neovim/neovim/wiki/Installing-Neovim).
2. Install the VSCode-Neovim extension from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=asvetliakov.vscode-neovim)
3. After installation, specify the path to your Neovim executable in your settings.json file.
4. You can also customize keybindings in your keybindings.json file, and use a lua file for additional customization. Example configurations can be found [here](https://github.com/vscode-neovim/vscode-neovim).

## Usage

To begin using Vim commands in Visual Studio Code, just open a file and start editing. Remember that the modes (insert, normal, visual) are a key part of Vim, and if you're not familiar with them, you should look into a [Vim tutorial](https://www.openvim.com/).

## File Reference

The repository includes several configuration files that are needed to set up and customize VSCodeVim and VSCode-Neovim:

- [vim-settings.json](./vim-settings.json): Contains settings for the VSCodeVim extension. Copy its content to your VS Code `settings.json` file.
- [keybindings.json](./keybindings.json): Contains custom keybindings for the VSCode-Neovim extension. Copy its content to your VS Code `keybindings.json` file.
- [nvim-settings.json](./nvim-settings.json): Contains settings for the VSCode-Neovim extension. Copy its content to your VS Code `settings.json` file.
- [vs-code.lua](./vs-code.lua): Lua configuration file for Neovim when used with the VSCode-Neovim extension. You need to put this in your Neovim configuration directory.

Please make sure to adjust the file paths according to your system configuration and needs.

## Comparison: VSCodeVim vs. VSCode-Neovim

Here are some pros and cons of using VSCodeVim versus VSCode-Neovim:

### VSCodeVim

Pros:

- More lightweight.
- Doesn't require installing and integrating an external tool (Neovim).
- Simpler setup and configuration.
- Generally enough for basic Vim keybinding emulation.

Cons:

- Might not support all advanced Vim features.

### VSCode-Neovim

Pros:

- Full Vim emulation with support for advanced Vim features.
- Can use Neovim configurations and plugins.

Cons:

- Requires installing Neovim on your system and setting up the integration in VS Code.
- More complex configuration.

Remember to choose the extension that best suits your needs and level of comfort with Vim and/or Neovim.

## Receipt

### LazyVim in VSCode

LazyVim is a powerful and lightweight Neovim configuration. With VSCode-Neovim, you can also utilize LazyVim inside VSCode for an optimized Vim experience.

1. Install LazyVim following the instruction on [LazyVim's website](https://www.lazyvim.org)
2. Update your `vs-code.lua` based on the configuration provided [here](https://www.lazyvim.org/plugins/extras/vscode)
3. Additional tips and configuration examples can be found [here](https://www.lazyvim.org/configuration/tips)

## Video Tutorials

Here are some video tutorials that can help you get started:

[![IT Man - Talk #35 #Neovim IDE for Web Developer [Vietnamese]](https://i.ytimg.com/vi/3EbgMJ-RcWY/mqdefault.jpg)](https://www.youtube.com/watch?v=3EbgMJ-RcWY)

[![IT Man - Talk #33 NeoVim as IDE [Vietnamese]](https://i.ytimg.com/vi/dFi8CzvqkNE/mqdefault.jpg)](https://www.youtube.com/watch?v=dFi8CzvqkNE)

## Author

- Website: https://productsway.com/
- Twitter: [@jellydn](https://twitter.com/jellydn)
- Github: [@jellydn](https://github.com/jellydn)

## Show your support

Give a ⭐️ if this project helped you!
