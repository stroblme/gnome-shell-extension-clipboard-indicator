# 📋 Clipboard Indicator x Mathpix

See the original [Gnome Shell Extension Clipboard Indicator](https://github.com/Tudmotu/gnome-shell-extension-clipboard-indicator) for details.

This fork adds support for [Mathpix](https://mathpix.com/) and allows to convert images in the clipboard into latex code.
This functionality requires an API key which can be obtained from the [Mathpix account page](https://accounts.mathpix.com/). 

## 📦 Install from source (modified urls)

Installation via git is performed by cloning the repo into your local gnome-shell extensions directory (usually `~/.local/share/gnome-shell/extensions/`)

```
git clone https://github.com/stroblme/gnome-shell-extension-clipboard-indicator <extensions-dir>/clipboard-indicator@stroblme.com
```

After cloning the repo, the extension is practically installed yet disabled. In order to enable it, run the following command::
```
gnome-extensions enable clipboard-indicator@stroblme.com
```
