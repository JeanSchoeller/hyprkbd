# hyprkbd - On-screen keyboard for Hyprland


This project is a fork from the wvkbd designed for wlroot. 
We aim to bring this to aquamarine and further expand the reach to fully usable touchscreen in Hyprland.

## Roadmap

 - [ ] Typing, modifier locking, layout switching
 - [ ] Positive visual feedback on key presses
 - [ ] Custom layouts and underlying keymaps
 - [ ] On-the-fly layout and keymap switching
 - [ ] Custom color schemes
 - [ ] Proper font drawing
 - [ ] Intuitive layouts
 - [ ] International layouts (cyrillic, arabic, persian, greek, georgian)
 - [ ] Support for 'Copy' keys which are not on the keymap
 - [ ] Emoji support
 - [ ] Compose key for character variants (e.g. diacritics)
 - [ ] Show/hide keyboard on signals (SIGUSR1 = hide, SIGUSR2 = show, SIGRTMIN = toggle)
 - [ ] Automatic portrait/landscape detection and subsequent layout switching
 - [ ] Make sure the virtual input method in wayland is working as best as it can
 - [ ] Support for input method protocol in wayland, ability to respond to text
   fields

## Related projects

* [clickclack](https://git.sr.ht/~proycon/clickclack) - Audio/haptic feedback (standalone)
* [swipeGuess](https://git.sr.ht/~earboxer/swipeGuess) - Word-completion for swipe-typing
* [Sxmo](https://sxmo.org) - A hackable mobile interface environment for Linux phones that adopted wvkbd as its keyboard
* [svkbd](https://tools.suckless.org/x/svkbd/) - A similar project as wvkbd but for X11 rather than Wayland
* [squeekboard](https://gitlab.gnome.org/World/Phosh/squeekboard) - The virtual keyboard developed for the Librem5 (used
	by Phosh)

