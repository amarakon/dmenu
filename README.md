dmenu
================

## Contents

-   [Patches](#patches)

This is my custom build of dmenu. It includes some excellent feauteres I
added in myself that you will not see in any other dmenu build. For
example, the caret is colored and it does not move when typing a
password.

## Patches

| Feature                               | Patch                                                                                                                                   |
|:--------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------|
| Color fonts (emojis) work             | [allow-color-font](https://github.com/amarakon/dotfiles/tree/master/etc/portage/patches/x11-misc/dmenu/dmenu-allow-color-font-5.0.diff) |
| Colored caret                         | [colored-caret](https://github.com/amarakon/dotfiles/tree/master/etc/portage/patches/x11-misc/dmenu/dmenu-colored-caret-5.0.diff)       |
| Paste with tradiotional keybindings   | [easypaste](https://github.com/amarakon/dotfiles/tree/master/etc/portage/patches/x11-misc/dmenu/dmenu-easypaste-5.0.diff)               |
| Select multiple items                 | [multi-selection](https://github.com/amarakon/dotfiles/tree/master/etc/portage/patches/x11-misc/dmenu/dmenu-multi-selection-4.9.diff)   |
| Use dmenu for password authentication | [password](https://github.com/amarakon/dotfiles/tree/master/etc/portage/patches/x11-misc/dmenu/dmenu-password-5.0.diff)                 |
