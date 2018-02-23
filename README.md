# Pomodoro for elementary OS - Wingpanel Indicator

TODO: Put a screenshot

## Building and Installation

You'll need the following dependencies:

    libglib2.0-dev
    libgranite-dev
    libgtk-3-dev
    libwingpanel-2.0-dev
    meson
    valac

Run `meson` to configure the build environment and then `ninja` to build

    meson build --prefix=/usr
    ninja -C build

To install, use `ninja install`

    sudo ninja install

And restart wingpanel

  `pkill wingpanel`
