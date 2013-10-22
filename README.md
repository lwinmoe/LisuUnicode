# Lisu Unicode keyboard for Linux

## How to install the keyboard

Keyboard layout is defined in `lis`. It has to be copied to the `/usr/share/X11/xkb/symbols/` 
directory. You will also need to add the content of evdev.xml to evdev.xml in `/usr/share/X11/xkb/rules`. Make sure the XML entry is correctly entered into evdev.xml.

### Notes on the keyboard layout

* Lisu tone mark `MYA CYA`(ꓺ) is `Shift + .`
* Lisu punctuation comma (꓾) is `Shift + n` or `minus sign`
* Lisu punctuation full stop (꓿) is `Shift + m` or `equal sign`
