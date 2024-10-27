# WezTerm Configuration

## Install and Configure WezTerm

Following are the instructions to configure WezTerm. This document assumes that you have WezTerm installed. Install a Nerd font of your choice from [https://www.nerdfonts.com/font-downloads](https://www.nerdfonts.com/font-downloads) and use in in the config.

### Configure WezTerm

Once WezTerm is installed, you can launch it. The default look and feel might not be very appealing, so let's configure it to make it beautiful.

Create a new folder called `wezterm` inside your `.config` directory and navigate into it:
```
cd ~/.config
mkdir wezterm
cd wezterm
```

Create a new file named `wezterm.lua`:
```
touch wezterm.lua
```

Open this file in an editor of your choice. I used Neovim, but feel free to use any editor you prefer.

Using Neovim (if you have it installed):

```
nvim wezterm.lua
```

Copy-Paste the contents of the config in this repository and restart the terminal.

Enjoy!!!