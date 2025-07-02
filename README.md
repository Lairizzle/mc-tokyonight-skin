# Tokyo Night for Midnight Commander

A clean, modern Midnight Commander skin inspired by the [Tokyo Night Neovim theme](https://github.com/folke/tokyonight.nvim) — perfect for fans of elegant dark UI with soft contrast and vibrant accents.

This theme brings full Tokyo Night aesthetics to your terminal file manager, blending seamlessly with terminals using the [Tokyo Night color palette](https://github.com/davidmathers/tokyo-night-kitty-theme), including Kitty, Alacritty, and WezTerm.

---

## Features

- True 256-color support
- Carefully matched colors to the Neovim `tokyonight.nvim` theme
- Low-contrast backgrounds (`#1f2335`) with bright foregrounds (`#c0caf5`)
- Highlight colors for selections, hotkeys, menus, and file types
- Calm but readable contrast levels for extended terminal use

## Installation

### Quick Install

```bash
# Create the skins directory
mkdir -p ~/.local/share/mc/skins/

# Download the skin file
curl -o ~/.local/share/mc/skins/tokyonight.ini https://raw.githubusercontent.com/lairizzle/mc-tokyonight-skin/main/tokyonight.ini

# Configure MC to use the theme
echo "skin=tokyonight" >> ~/.config/mc/ini
```

### Manual Install

```
# Create the skins directory if it doesn't exist
mkdir -p ~/.local/share/mc/skins/
```

Download the skin file (tokyonight.ini) from the repository:

    Visit https://github.com/lairizzle/mc-tokyonight-skin

    Download or copy the tokyonight.ini file

Copy the skin file into the skins directory:

```
cp /path/to/downloaded/tokyo-night.ini ~/.local/share/mc/skins/
```
Once copied open MC > Options > Appearance > Select tokyonight as skin.

