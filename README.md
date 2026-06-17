# Gradient — a Tesserae theme pack

The 14 linear-gradient surface themes that shipped bundled with Tesserae through v0.47.8. In v0.47.9 they moved to the catalog so the bundle stays slim and the same themes are now opt-in.

| Theme | Tagline |
|---|---|
| `sunset` | orange → amber |
| `aurora` | teal → magenta |
| `twilight` | violet night |
| `spectrum` | full pop |
| `coral` | peach → blush |
| `mist` | blue-gray → lavender |
| `sand` | cream → taupe |
| `sage` | moss → teal |
| `linen` | cream → gold |
| `mauve` | rose → lavender |
| `marble` | ivory → pale stone |
| `glacier` | teal → mint |
| `honey` | butter → amber |
| `pearl` | blush → cream |

Each theme uses Spectra's `--surface-gradient` opt-in token to paint `.w` cells with a linear gradient. The renderer's Floyd-Steinberg dither approximates the gradient on the panel palette; pairs especially well with 7-colour Spectra panels.

## Install

Via the catalog: **Tesserae → Settings → Widgets → Browse community widgets**, find "Gradient", hit Install.

Requires **Tesserae 0.47.9 or newer** (until 0.47.9 these themes were still bundled — the install path would refuse on an id clash).

## Restoring dashboards after upgrade

If you have a dashboard pinned to one of these themes and upgrade to 0.47.9 without installing this pack, the picker won't list it and the cascade will fall back to Light. Installing the pack restores every dashboard's appearance, no further action needed.

## License

AGPL-3.0-or-later. See [LICENSE](./LICENSE).
