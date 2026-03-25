## Overview

Linux ricing refers to making aesthetic improvements and customizations to your Linux desktop environment, creating a unique and visually appealing system that reflects personal preferences.

## Features

### Window Managers

#### Tiling Window Managers
- **i3/i3-gaps**: Manual tiling window manager
  - Easy to configure
  - Great for productivity
  - Large community
  - Gaps between windows support

- **bspwm**: Binary space partitioning window manager
  - Pure window management
  - Configured via shell
  - Minimal and fast
  - Flexible tiling algorithms

- **Hyprland**: Dynamic tiling Wayland compositor
  - Modern and smooth animations
  - Native Wayland support
  - Dynamic window management
  - Highly customizable

- **sway**: i3-compatible Wayland compositor
  - Drop-in replacement for i3
  - Wayland native
  - Better multi-monitor support

- **dwm**: Dynamic window manager
  - Extremely minimal (< 2000 SLOC)
  - Configured by editing source
  - Very fast and lightweight

#### Stacking/Floating Window Managers
- **AwesomeWM**: Highly configurable framework WM
  - Lua-based configuration
  - Built-in widgets
  - Dynamic or tiling layout
  - Extensive documentation

- **Openbox**: Lightweight stacking window manager
  - XML configuration
  - Minimal resource usage
  - Works with multiple desktop environments

### Terminal Emulators

#### Modern Terminals
- **Alacritty**: GPU-accelerated terminal
  - Fast rendering
  - Cross-platform
  - YAML configuration
  - No GUI, pure terminal

- **kitty**: GPU-based terminal with features
  - Image support
  - Ligatures
  - Splits and tabs
  - Extensible with Python

- **WezTerm**: GPU-accelerated terminal
  - Cross-platform
  - Lua configuration
  - Multiplexing built-in
  - Unicode support

#### Classic Terminals
- **URxvt**: Lightweight Unicode terminal
- **st (simple terminal)**: Suckless terminal
- **Termite**: VTE-based keyboard-centric terminal

### Bars and Panels

#### Status Bars
- **Polybar**: Highly customizable status bar
  - Module-based configuration
  - Multiple monitor support
  - IPC support
  - Many built-in modules

- **waybar**: Customizable Wayland bar
  - CSS styling
  - JSON configuration
  - Module system
  - Wayland native

- **i3status/i3blocks**: Minimalist status bars
- **lemonbar**: Lightweight bar
- **eww** (Elkowar's Wacky Widgets): Widget system

### Application Launchers

- **Rofi**: Window switcher and application launcher
  - Highly customizable
  - Multiple modes
  - Theme support
  - Script integration

- **dmenu**: Dynamic menu for X
  - Minimal and fast
  - Suckless philosophy
  - Scriptable

- **wofi**: Wayland rofi alternative
- **Ulauncher**: Application launcher for Linux
- **Albert**: Desktop agnostic launcher

### Color Schemes

#### Popular Themes
- **Catppuccin**: Pastel color palette
  - Multiple flavors
  - Wide application support
  - Active community

- **Gruvbox**: Retro groove colors
  - Dark and light variants
  - Warm, earthy tones
  - Very popular

- **Nord**: Arctic color palette
  - Cool, bluish tones
  - Clean and minimal
  - Extensive ports

- **Dracula**: Dark theme
  - High contrast
  - Vibrant colors
  - 200+ ports

- **Tokyo Night**: Dark theme
  - Inspired by Tokyo's night skyline
  - Multiple variants
  - Modern aesthetic

- **One Dark**: Atom's dark theme
- **Solarized**: Precision colors for machines and people
- **Palenight**: Material theme variant

### Compositor and Effects

#### X11 Compositors
- **picom**: Lightweight compositor
  - Shadows and transparency
  - Blur and rounded corners
  - Smooth animations
  - Fork of compton

- **compton**: Original compositor (deprecated)

#### Wayland Compositors
- Hyprland, sway (built-in composition)
- wlroots-based compositors

### Dotfile Management

#### Tools
- **GNU Stow**: Symlink farm manager
- **chezmoi**: Dotfiles manager
- **yadm**: Yet another dotfiles manager
- **dotbot**: Dotfile installation tool
- **Home Manager**: Nix-based dotfile management

### File Managers

#### Terminal File Managers
- **ranger**: Vi-like file manager
- **lf**: List files, ranger alternative
- **nnn**: Fastest terminal browser
- **vifm**: Ncurses-based file manager

#### GUI File Managers
- **Thunar**: Lightweight GTK file manager
- **PCManFM**: Extremely fast file manager
- **Nautilus**: GNOME file manager

### System Information

- **neofetch**: System info script
- **fastfetch**: Faster neofetch alternative
- **pfetch**: Minimal fetch script
- **screenfetch**: Bash screenshot information tool

### Notification Daemons

- **dunst**: Lightweight notification daemon
- **mako**: Lightweight Wayland notification daemon
- **notify-osd**: Canonical's notification daemon

### Wallpaper Tools

- **feh**: Image viewer and wallpaper setter (X11)
- **nitrogen**: Wallpaper browser and setter
- **swaybg**: Wallpaper tool for Wayland
- **hyprpaper**: Wallpaper utility for Hyprland
- **variety**: Wallpaper manager with effects

### Fonts

#### Monospace Fonts
- **JetBrains Mono**: Developer font with ligatures
- **Fira Code**: Monospaced with programming ligatures
- **Hack**: Typeface designed for source code
- **Source Code Pro**: Adobe's monospaced font
- **Cascadia Code**: Microsoft's terminal font
- **Nerd Fonts**: Patched fonts with icons

### GTK/Qt Theming

#### GTK Themes
- Adapta, Arc, Materia
- Gruvbox-GTK, Dracula-GTK
- Catppuccin-GTK, Nord-GTK

#### Icon Themes
- **Papirus**: Icon theme with  many variants
- **Numix**: Flat icon theme
- **La Capitaine**: macOS-inspired icons

### Configuration Showcases

#### Inspiration
- r/unixporn (Reddit community)
- dotfiles.github.io
- GitHub topics: #dotfiles, #ricing
- Awesome WM configurations gallery

## Use Cases

- Creating minimalist productive workspaces
- Building highly customized desktop environments
- Learning Linux system configuration
- Optimizing workflow with tiling WMs
- Sharing aesthetically pleasing setups
- Developing unique personal computing environments

## Pricing

All tools and resources are free and open-source, typically under GPL, MIT, or similar licenses.