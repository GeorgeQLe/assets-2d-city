# assets-2d-city

2D city and urban-themed game assets (buildings, roads, vehicles, props)

## Structure

```
assets-2d-city/
├── assets/          # Original or normalized asset files
├── previews/        # Thumbnails and contact sheets
├── LICENSES/        # Original license files
├── examples/        # Tiny usage previews
├── manifest.json    # Machine-readable asset index
├── tags.json        # Genre, theme, style tags
└── README.md
```

## Usage

Browse `manifest.json` for a machine-readable index of all assets. Each entry includes:

- `id`: Unique asset identifier
- `path`: Relative path to the asset file
- `source`: Original asset pack name
- `license`: SPDX license identifier
- `tags`: Searchable tags

## Adding Assets

1. Place asset files in `assets/<source-pack>/`
2. Add license info to `LICENSES/`
3. Generate a preview in `previews/`
4. Add an entry to `manifest.json`

## License

Individual assets retain their original licenses. See `LICENSES/` and each asset's `license` field in `manifest.json`.
