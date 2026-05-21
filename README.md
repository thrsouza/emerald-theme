<div align="center">

<img src="https://raw.githubusercontent.com/thrsouza/emerald-theme/master/icon.png" width="140" />

# Emerald Theme

Deep midnight darks and crisp lights for VS Code, tied together by a single emerald glow.

![preview-dark](https://raw.githubusercontent.com/thrsouza/emerald-theme/master/emerald-dark-preview.png)

![preview-light](https://raw.githubusercontent.com/thrsouza/emerald-theme/master/emerald-light-preview.png)

</div>

## Variants

- **Emerald Dark** — near-black midnight surfaces (`#050505` / `#0c0c0c` / `#111111`) with emerald accents throughout the UI.
- **Emerald Light** — clean white surfaces with a deeper emerald accent (`#006b5e` / `#00b8a6`) tuned for contrast.

## Palette

| Role            | Dark                  | Light                 |
| --------------- | --------------------- | --------------------- |
| Background      | `#050505` – `#111111` | `#ffffff` – `#f3f5f4` |
| Foreground      | `#e5e5e5`             | `#101828`             |
| Accent          | `#00d2be`             | `#00b8a6` / `#006b5e` |
| Accent (bright) | `#4dffd9`             | `#00d2be`             |
| Accent (deep)   | `#006b5e`             | `#006b5e`             |

## Installation

### From the Marketplace

1. Open the **Extensions** view (`Ctrl/Cmd + Shift + X`).
2. Search for **Emerald Theme**.
3. Click **Install**.

### Selecting the theme

Open the Command Palette (`Ctrl/Cmd + K` then `Ctrl/Cmd + T`) or run **Preferences: Color Theme**, then pick **Emerald Dark** or **Emerald Light**.

## Development

Clone the repository and open it in VS Code:

```bash
git clone https://github.com/thrsouza/emerald-theme.git
cd emerald-theme
code .
```

Press `F5` to launch an **Extension Development Host** window with the theme loaded, then select it via **Preferences: Color Theme**. Edits to the files in [`themes/`](./themes) are reflected live.

The theme definitions live in:

- [`themes/emerald-dark.json`](./themes/emerald-dark.json)
- [`themes/emerald-light.json`](./themes/emerald-light.json)

## License

Released under the [MIT License](./LICENSE).
