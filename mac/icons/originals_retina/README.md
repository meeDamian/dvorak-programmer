### Retina icons

All those icons are already on your mac in a file here: `/System/Library/Keyboard Layouts/AppleKeyboardLayouts.bundle/Contents/Resources/AppleKeyboardLayouts-L.dat`.

It's quite tricky to extract them, though.

I, following [this advice](http://apple.stackexchange.com/questions/147820/how-to-extract-keyboard-layout-icon/147853#147853), used [this repository](https://github.com/phible/scripts).

Relevant command:

```bash
curl https://raw.githubusercontent.com/phible/scripts/master/apple-kbd-dat-icon-extract.py -o a.py
mkdir icons
python a.py -o icons
```