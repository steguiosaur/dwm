# dwm - dynamic window manager

**dwm** configuration by steguiosaur

dwm is an extremely fast, small, and dynamic window manager for X.

## Requirements

In order to build dwm you need the Xlib header files.

## Install

Edit `config.mk` to match your local setup (dwm is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install dwm (if
necessary as root):

```console
make clean install
```

## Patches

Visit dwm patches at [https://dwm.suckless.org/patches/](https://dwm.suckless.org/patches/)

```console
patch -p1 < st-patch.diff
```

- `dwm-actualfullscreen-20211013-cb3f58a.diff`
- `dwm-alttagsdecoration-2020010304-cb3f58a.diff`
- `dwm-alwayscenter-20200625-f04cac6.diff`
- `dwm-bar-height-6.2.diff`
- `dwm-barpadding-20211020-a786211.diff`
- `dwm-fullgaps-6.4.diff`
- `dwm-push-20160731-56a31dc.diff`
- `dwm-swallow-6.3.diff`

