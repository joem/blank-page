# Blank Page

A single-file browser canvas — just a white screen and a help box. Useful as a
backdrop for presentations, focus sessions, or anything where you want a clean,
controllable background color.

Open `index.html` directly in any modern browser. No server, build step, or
dependencies required.

## Keybindings

| Key | Action |
|-----|--------|
| `F` | Toggle fullscreen |
| `R` | Jump to a random color |
| `C` | Start cycling through colors smoothly |
| `Space` | Stop color cycling |
| `Esc` | Exit fullscreen |

All bindings are also clickable in the help box.

## Help box

The help box appears on load and whenever you press a key or click the
background. It fades out after a few seconds of inactivity, but stays visible
while the mouse is inside it. The cursor hides after a few seconds of no mouse
movement and reappears when you move the mouse or the help box is visible.

## Preset colors

Two rows of swatches let you jump to a specific color instantly:

- **Lighter** — full white, near-white, and a set of soft neutral tones
  (warm grey, cool grey, sage, dusty blue, dusty rose, dusty lavender)
- **Darker** — full black, near-black, and matching dark neutral tones

## Hex input

A text field at the bottom of the help box shows the current background color
as a hex code and updates live while colors are cycling. Type any valid hex
value (`#rrggbb` or `#rgb`) and press a key or click away to apply it.

## Color cycling

Press `C` to smoothly fade through the full hue range at roughly constant
perceived brightness. Press `Space` (or click "Stop color cycling") to freeze
on the current color immediately.
