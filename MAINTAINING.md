# Notes

- `README.md` is what shows up on [github.com/FoXs1953](https://github.com/FoXs1953).
- `assets/header.svg` is the banner, `assets/header-mobile.svg` is the narrow one GitHub shows under 600px. The text in both is plain SVG `<text>`, so it's easy to edit by hand.
- `assets/stack/` has the stack badges. To add or change one, edit `BADGES` in `tools/generate_badges.py` and run:

```sh
python3 tools/generate_badges.py
```

Badges switch between dark and light colors with the viewer's theme. Logo credits are in `assets/stack/NOTICE.md`.
