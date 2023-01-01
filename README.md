# Everforest for Wez's Terminal

## Introduction
This is a port of the amazing [Everforest](https://github.com/sainnhe/everforest) theme to the also amazing [Wez's Terminal](https://github.com/wez/wezterm) emulator.

Please checkout their Github pages for more information.

## Instalation

### Using the install script

1. Run the installation script:
```
$ git clone https://github.com/frdwin/Everforest-Wezterm && \
cd Everforest-Wezterm && \
./install.sh
```

2. Change your WezTerm config to apply the theme:
```
return {
	[... your configuration ...]
	color_scheme_dirs = { "colors" },
	color_scheme = "Everforest Dark (Medium)",
}
```

### Manually

### Options

Possible values for the color_scheme variable are:

* "Everforest Dark (Soft)"
* "Everforest Dark (Medium)"
* "Everforest Dark (Hard)"
* "Everforest Light (Soft)"
* "Everforest Light (Medium)"
* "Everforest Light (Hard)"
