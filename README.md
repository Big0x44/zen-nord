# Zen Nord

A dark [Nord](https://www.nordtheme.com/) theme for Zen Browser. 

## Install

1. In Zen, open `about:support` and click **Open Profile Folder** (the label may vary by OS). Use the active profile's root folder.
2. Create a `chrome` directory there if it does not exist.
3. Copy `nord.css` and `userChrome.css` from this repository into `chrome`. Copy `userContent.css` too if you want Nord on New Tab, Home, blank pages, Settings, Add-ons, Downloads, and `about:config`.
4. Open `about:config`, find `toolkit.legacyUserProfileCustomizations.stylesheets`, and set it to `true`.
5. Choose Zen's dark appearance in Settings for consistent native controls. Fully quit and reopen Zen, including any other open windows.

```text
<your active profile>/
└── chrome/
    ├── nord.css
    ├── userChrome.css
    └── userContent.css   (optional)
```

## Palette and roles

All sixteen source colors are defined once in `nord.css`, using the exact hex values from [Nord's Colors and Palettes guide](https://www.nordtheme.com/docs/colors-and-palettes/). The theme uses the dark ambiance roles:

| Palette | Colors | Theme role |
| --- | --- | --- |
| Polar Night | `nord0`–`nord3` | Base background, raised panels/inputs, selected surfaces, subtle borders |
| Snow Storm | `nord4`–`nord6` | Readable text, hover/emphasis, active text |
| Frost | `nord7`–`nord10` | Complementary accent, primary accent/focus, secondary accent, reserved tertiary accent |
| Aurora | `nord11`–`nord15` | Errors, reserved danger color, warnings, success, private/visited indicators |
