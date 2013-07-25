# Lisu Unicode font and keyboard for Linux

I wrote the keyboard layout. The font is modifed from Lisu font made by GW SI using 
[FontForge](http://fontforge.org/).

## How to install the font

You can copy the font file `NgwaLisu.ttf` to `.fonts/` directory in your home folder. 

## How to install the keyboard

Keyboard layout is defined in `lis`. It has to be copied to the `/usr/share/X11/xkb/symbols/` 
directory. You will also need to add the content of evdev.xml to evdev.xml in `/usr/share/X11/xkb/rules`. Make sure the XML entry is correctly entered into evdev.xml.
