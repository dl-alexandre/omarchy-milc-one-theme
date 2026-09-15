# MILC One

Light [Omarchy](https://omarchy.org/) theme from [MILC Group](https://milcgroup.com/) / [ONE](https://dev.milcgroup.com/) — sage cream `#dee4d2`, forest green `#2f6f57`, olive `#5d820e`.

Pair: [dark variant](https://github.com/dl-alexandre/omarchy-milc-one-dark-theme)

## Install

```bash
omarchy theme install https://github.com/dl-alexandre/omarchy-milc-one-theme.git
```

Or *Install > Style > Theme* and paste that URL.

## About and screensaver

Omarchy never applies a theme's About/fastfetch logo or screensaver by itself. A `theme-set` hook does that.

You can have several theme-set hooks. There is only **one branding hook**, named `theme-set-branding`. This theme and the Alexandre Family Farm pair ship the same file, so install it **once per machine**:

```bash
omarchy hook install theme-set ~/.config/omarchy/themes/milc-one/theme-set-branding
omarchy theme set milc-one
```

After that, every theme switch runs it automatically. Do not reinstall it when changing light/dark or between MILC and AFF. Re-run `omarchy hook install` only if `theme-set-branding` in this repo changed.

## Preview

![preview](preview.png)

## License

All rights reserved. Personal Omarchy use only; MILC Group / ONE marks stay with MILC Group.
