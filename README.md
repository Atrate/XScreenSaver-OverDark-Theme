# XScreenSaver OverDark Theme
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md) 

## Description
A dark theme for XScreenSaver based on a [2011 Ask Ubuntu answer](https://askubuntu.com/a/85196).

## Screenshots
![Screenshot 1](./screenshot.png)

## Installation
1. Install the `terminus` font
2. Execute `curl 'https://gitlab.com/Atrate/xscreensaver-overdark-theme/-/raw/master/.Xresources' >> ~/.Xresources && xrdb -merge ~/.Xresources`
3. Restart XScreenSaver: `killall xscreensaver && xscreensaver &`

## Uninstalation
1. Remove the lines for the theme from `~/.Xresources`
2. Restart `X` (log out and log in/restart computer)

## Credits
- `fossfreedom` for their [Ask Ubuntu answer](https://askubuntu.com/a/85196).

## License
This project is licensed under the [GPL-3.0-or-later](https://www.gnu.org/licenses/gpl-3.0.html).
