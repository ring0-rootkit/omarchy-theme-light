# Miraculous Light -- An Omarchy Theme

> *"In the daytime, I'm Marinette -- just a normal girl with a normal life.
> But there's something about me that no one knows yet..."*

A light [Omarchy](https://omarchy.dev) theme inspired by **Marinette Dupain-Cheng's** daytime Paris.
Warm sunlight streaming through cafe windows, cherry blossoms drifting over the Seine,
the pastel facades of Montmartre, and espresso on a sidewalk terrace.

Ladybug red on warm parchment. Rose accents against sunlit stone.
Sketchbooks open on wrought-iron tables.

This is the light-mode companion to the dark [Miraculous](https://github.com/ring0-rootkit/omarchy-r0-theme) theme.

---

## Palette

```
   ██████  Ladybug Red     #C62828   — her suit, bold on daylight
   ██████  Rose Pink       #C2185B   — marinette's signature
   ██████  Dark Gold       #B8860B   — miraculous jewels in sun
   ██████  Forest Green    #2E7D32   — thread and fabric
   ██████  Seine Blue      #0277BD   — the river seine at noon
   ██████  Violet          #6A1B9A   — fashion accents
   ██████  Teal            #00838F   — cool contrast
   ██████  Muted Grey      #8E99A4   — steel and silence
   ██████  Warm Border     #E0D8D0   — café stone
   ██████  Soft Selection  #E8D5DC   — cherry blossom highlight
   ██████  Linen Alt       #F0EDE8   — parchment in shade
   ██████  Warm White      #FAFAF8   — the background of it all
```

## What's Themed

| Component | File | What it styles |
|-----------|------|----------------|
| Hyprland | `hyprland.conf` | Window borders, shadows, groupbar |
| Hyprlock | `hyprlock.conf` | Lock screen colors |
| Waybar | `waybar.css` | Status bar, workspaces, system info |
| Ghostty | `ghostty.conf` | Terminal colors (16-color palette) |
| Alacritty | `alacritty.toml` | Terminal colors (16-color palette) |
| btop | `btop.theme` | System monitor graphs and meters |
| Mako | `mako.ini` | Notification styling |
| Wofi | `wofi.css` | App launcher |
| Walker | `walker.css` | App launcher (walker) |
| SwayOSD | `swayosd.css` | Volume/brightness OSD |
| Neovim | `neovim.lua` | Editor (via miraculous-light.nvim plugin) |
| Icons | `icons.theme` | Tela-circle-pink icon pack |

## Installation

### Quick (Omarchy Menu)

**Super + Alt + Space** -> Install -> Style -> Theme -> paste the repo URL.

### Manual

```bash
git clone git@github.com:ring0-rootkit/omarchy-theme-light.git \
  ~/.config/omarchy/themes/miraculous-light
```

### Neovim Plugin

The `neovim.lua` points to [miraculous-light.nvim](https://github.com/ring0-rootkit/miraculous-light.nvim)
for full Treesitter + LSP editor theming. Install it separately if you want the
complete experience.

---

*Spots on -- time to shine.*
