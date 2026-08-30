# Mavik

[![CI](https://github.com/Sam-DarkBall-Mods/Mavik/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Mavik/actions/workflows/ci.yml)

Mavik adds Mavik 3 and Mavik 3T reconnaissance drones for BLUFOR, OPFOR and
Independent. The mod includes a flight HUD, signal calculation, battery
replacement, inventory packing and support for a grenade drop attachment.

## Requirements

- Arma 3 2.22 or newer
- CBA_A3

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The game still loads assets from the `mavik` prefix, and releases keep the
`mavik.pbo` filename.

## License

Code and configs use GPL-2.0-or-later. Original drone models, textures,
materials and audio use APL-SA. See [LICENSES.md](LICENSES.md).
