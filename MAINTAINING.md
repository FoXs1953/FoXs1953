# Updating this profile

`README.md` is displayed on [github.com/FoXs1953](https://github.com/FoXs1953) by the public `FoXs1953/FoXs1953` repository.

## Content

Edit the README to change the introduction, project links or technologies. Keep the main stack focused on tools used in application code. Additional languages and experiments live in the expandable section. Team projects should retain their team attribution.

## Visual assets

- `assets/header.svg` — desktop banner.
- `assets/header-mobile.svg` — compact banner, selected by the README's `<picture>` element below 600px.
- `assets/stack/` — individual, locally hosted vector badges. Each badge links to the technology's documentation.
- `tools/generate_badges.py` — regenerate the badge SVGs with Python 3. It uses stored icon paths and requires no network or third-party Python packages.

```sh
python3 tools/generate_badges.py
```

The graphite backgrounds keep the badges readable in GitHub's light and dark themes. Separate images wrap naturally on narrow screens. GitHub renders the assets without JavaScript, inline page CSS, external image services or API tokens.

Technology logo sources and attribution are in `assets/stack/NOTICE.md`. The header and badge frame are custom artwork.
