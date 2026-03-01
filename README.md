# Cursor Theme for Zed

[![Zed Extension](https://img.shields.io/badge/-Zed_Extension-blue?style=flat&logo=zedindustries&logoColor=%23FFFFFF&logoSize=auto&labelColor=%23111111&color=%23084CCF)](https://zed.dev/extensions/cursor-theme)

Cursor inspired theme for [Zed](https://zed.dev).

## Screenshot

### Light

![Light](screenshots/light.png)

### Dark

![Dark](screenshots/dark.png)

## Usage

Setup auto switch theme in light and dark mode based on the system's appearance.

Open your Zed user settings.json: `~/.config/zed/settings.json`, and add this config:

```json
{
  "theme": {
    "mode": "system",
    "light": "Cursor Light",
    "dark": "Cursor Dark"
  }
}
```

## License

MIT
