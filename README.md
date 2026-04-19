# Theme2Crocs

A sleek dark Discord theme with customizable accent colors. Compatible with **Vencord** and **BetterDiscord**.

---

## Features

- **4 color presets** — Violet, Blue, Green, Red (switchable in seconds)
- **Fully customizable** — every color is a CSS variable you can tweak freely
- **Styled Spotify player** — blurred album art background, clean controls
- **Animated voice indicators** — glowing avatar ring when someone speaks
- **Custom code blocks** — ShikiCodeblocks integration with accent-colored header
- **Message cards** — subtle card effect with fade-in animation
- **Custom scrollbars** — accent-colored, appear on hover only
- **Styled context menus, tooltips, settings pages**
- **Status ring** on member list avatars (replaces the default dot)

---

## Installation

### Vencord
1. Install [Vencord](https://vencord.dev/) if you haven't already
2. Open Discord → **Vencord Settings** → **Themes** → **Online Themes**
3. Paste this URL and click **Load**:

```
https://raw.githubusercontent.com/diego2crocs/Theme2Crocs/main/Theme2Crocs.theme.css
```

### BetterDiscord
1. Install [BetterDiscord](https://betterdiscord.app/) if you haven't already
2. Download [`Theme2Crocs.theme.css`](https://raw.githubusercontent.com/diego2crocs/Theme2Crocs/main/Theme2Crocs.theme.css)
3. Move it to your BetterDiscord themes folder:
   - **Windows** : `%appdata%\BetterDiscord\themes\`
4. Open Discord → **BetterDiscord Settings** → **Themes** → enable **Theme2Crocs**

---

## Switching themes

Open `Theme2Crocs.theme.css` and uncomment the preset you want (comment out the others).

**Violet** (default)
```css
:root {
  --t-accent-rgb:       128, 66, 214;
  --t-badge-rgb:        236, 72, 153;
  /* ... */
}
```

**Blue**
```css
:root {
  --t-accent-rgb:       66, 120, 214;
  --t-badge-rgb:        72, 153, 236;
  /* ... */
}
```

**Green**
```css
:root {
  --t-accent-rgb:       46, 160, 100;
  --t-badge-rgb:        80, 210, 130;
  /* ... */
}
```

**Red**
```css
:root {
  --t-accent-rgb:       200, 60, 70;
  --t-badge-rgb:        236, 130, 72;
  /* ... */
}
```

---

## Custom colors

You can change any variable individually without switching preset. The key variables are:

| Variable | Role |
|---|---|
| `--t-accent-rgb` | Main accent color (R, G, B) |
| `--t-accent-mid-rgb` | Hover / glow color |
| `--t-accent-light-rgb` | Text accent color |
| `--t-badge-rgb` | Notification badge color |
| `--t-bg-0` → `--t-bg-6` | Background layers (darkest → lightest) |

Example — custom orange accent:
```css
:root {
  --t-accent-rgb:       220, 120, 40;
  --t-accent-mid-rgb:   240, 160, 80;
  --t-accent-light-rgb: 255, 200, 140;
  --t-badge-rgb:        220, 120, 40;
}
```

---

## Recommended plugins

These Vencord plugins pair well with this theme:

- **ShikiCodeblocks** — styled code blocks with syntax highlighting
- **SpotifyControls** — styled Spotify player in the sidebar
- **MentionAvatars** — avatar icons inside mention tags

---

## Author

Made by **Diego2Crocs**
