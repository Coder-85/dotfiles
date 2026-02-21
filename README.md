My personal dotfiles based on [Aurora](https://github.com/flickowoa/dotfiles/tree/aurora)

# Dependencies
For arch linux(Some are AUR packages):
```
hyprland-git waybar cava waybar-mpris-git python rustup kitty fish wofi xdg-desktop-portal-hyprland-git tty-clock-git swaylock grim wofi-emoji slurp starship jq macOS-hypr apple_cursor swaync wl-clipboard swaylock-effects-git helix neofetch
```

## For window borders
`rgb-borders` | rgb borders for grouped windows
```bash
git clone https://github.com/flick0/rgb-rs
cd rgb-rs
cargo build --release
cp ./target/release/rgb ~/.config/hypr/scripts/
```

## Note for Setup
Don't forget to add `hypr/scripts` and `hypr/scripts/tools` to PATH
