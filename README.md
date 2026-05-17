# assets-2d-city

2D city and urban-themed game assets (buildings, roads, vehicles, props)

## Stats

- **Total assets**: 1314
- **License**: CC0-1.0 (all Kenney assets are public domain)
- **Source**: [kenney.nl](https://kenney.nl)

## Source Packs

| Pack | Assets | License | Link |
|------|--------|---------|------|
| Kenney Retro Urban Kit | 688 | CC0-1.0 | [Link](https://kenney.nl/assets/retro-urban-kit) |
| Kenney Rpg Urban Pack | 490 | CC0-1.0 | [Link](https://kenney.nl/assets/rpg-urban-pack) |
| Kenney Tiny Town | 136 | CC0-1.0 | [Link](https://kenney.nl/assets/tiny-town) |

## Structure

```
assets-2d-city/
├── assets/kenney/    # Organized by source pack
├── previews/         # Pack preview images
├── LICENSES/         # License files per pack
├── manifest.json     # Machine-readable asset index (1314 entries)
├── tags.json         # Genre, theme, style tags
└── README.md
```

## Usage

Browse `manifest.json` for the full asset index. Each entry includes:

```json
{
  "id": "kenney-<pack>/<asset-name>",
  "name": "Human Readable Name",
  "path": "assets/kenney/<pack>/...",
  "source": "Kenney <Pack Name>",
  "sourceUrl": "https://kenney.nl/assets/<pack>",
  "license": "CC0-1.0",
  "tags": [...],
  "fileType": "png|ogg|obj|..."
}
```

## License

All assets are **CC0-1.0** (Creative Commons Zero) — public domain, free for any use including commercial, no attribution required. See `LICENSES/` for original license files from each pack.
