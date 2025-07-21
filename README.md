# Bluetooth Settings
[![Translation status](https://l10n.elementaryos.org/widget/settings/bluetooth/svg-badge.svg)](https://l10n.elementaryos.org/engage/settings/)

![screenshot](data/screenshot.png?raw=true)

## Building and Installation

You'll need the following dependencies:

* libadwaita-1-dev >=1.4.0
* libgranite-7-dev >=7.4.0
* libgtk-4-dev
* libswitchboard-3-dev
* meson
* valac

Run `meson` to configure the build environment and then `ninja` to build

    meson build --prefix=/usr
    cd build
    ninja

To install, use `ninja install`

    sudo ninja install
