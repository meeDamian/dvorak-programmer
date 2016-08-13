Dvorak - Programmer's
=====================

Currently only Polish (ISO) version for Mac is available, but I'll gladly accept any PR.

Click [here](https://github.com/chester1000/dvorak-programmer/blob/master/mac/Dvorak%20-%20Programmer's%20(Polish,%20ISO).pdf?raw=true) to see layout.

## Installation

###  Mac (via Ukelele)

1. Open Layout in Ukelele (`⌘o` & select `Dvorak - Pro.bundle`),
1. Select `File` from the top menu,
1. Select `Install` from the Submenu,
1. Choose desired option there.

###  Mac (via Terminal)

From repo root execute:

```bash
# To make this layout available to ALL USERS:
sudo cp -R mac/Dvorak\ -\ Pro.bundle /Library/Keyboard\ Layouts

# For current user only
# NOTE: Layout will *NOT* be available on the login screen
cp -R mac/Dvorak\ -\ Pro.bundle ~/Library/Keyboard\ Layouts
```

After that log out & log in again. In some cases restart might be necessary.
