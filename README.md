# Everforest
### for Wez's Terminal

## Introduction
This is a port of the amazing [Everforest](https://github.com/sainnhe/everforest) theme to the also amazing [Wez's Terminal](https://github.com/wez/wezterm) emulator.

Please checkout their Github pages for more information.

## Instalation

1. Clone the repo into wezterm config directory:
```
mkdir -p $HOME/.config/wezterm/ && \
git clone https://github.com/frdwin/Everforest-Wezterm $HOME/.config/wezterm/colors
```

2. Change your WezTerm config to apply the theme:
```
return {
	[... your configuration ...]
	color_scheme_dirs = { "~/.config/wezterm/colors" },
	color_scheme = "Everforest Dark (Medium)",
}
```

### Options

Possible values for the color_scheme variable are:

* "Everforest Dark (Soft)"
* "Everforest Dark (Medium)"
* "Everforest Dark (Hard)"
* "Everforest Light (Soft)"
* "Everforest Light (Medium)"
* "Everforest Light (Hard)"
