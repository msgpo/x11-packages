# Termux X11 Packages

<!--[![builds.sr.ht status](https://builds.sr.ht/~xeffyr/x11-packages.svg)](https://builds.sr.ht/~xeffyr/x11-packages?)-->
[![pipeline status](https://gitlab.com/xeffyr/x11-packages/badges/master/pipeline.svg)](https://gitlab.com/xeffyr/x11-packages/commits/master)

Here are located build scripts and patches for X11 packages for Termux.

To use X11-enabled programs, you need to install [VNC Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android) or [XServer XSDL](https://play.google.com/store/apps/details?id=x.org.server). If launching program from terminal, make sure that environment variable 'DISPLAY' is set to correct value, e.g. `export DISPLAY=:1` when using TigerVNC or `export DISPLAY=127.0.0.1:0` when XServer XSDL.

## How to enable this repository
To enable the [termux-x11.ml](https://termux-x11.ml) package repository run:

```
pkg install x11-repo
```

## Contributing

If you wish to contribute for this project, take a look on our [contributing guide](./CONTRIBUTING.md).

## External links

* Termux home page: https://termux.com/
* Termux Wiki: https://wiki.termux.com/wiki/Main_Page
* Termux App: https://github.com/termux/termux-app
* Termux Packages: https://github.com/termux/termux-packages
