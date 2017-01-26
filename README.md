# Scroll Past EOF

A plugin for [Brackets](https://github.com/adobe/brackets/)
which allows you to scroll below the document, stopping at the last line at top.

This plugin attempts to bring the same functionality to Brackets, as the
ScrollPastEOF plugin does for [Notepad++](https://notepad-plus-plus.org/)

This plugin offers a precisely calculated offset for the editor instead of the
fix 1000 pixels in the [Brackets Overscroll](https://github.com/Emmeran/brackets-overscroll)
plugin.

## Installation

* Open the Extension Manager in Brackets
* Search for "Scroll Past EOF"
* Click "Install"
* Reload Brackets by pressing F5

## Known issues, limitations

* The plugin does not support horizontally split screens
* When you resize brackets from a smaller size to a bigger, then the plugin does
not resizes properly - the fix is under progress

## Changelog

= [0.0.3](https://github.com/meszaros-lajos-gyorgy/brackets-scroll-past-eof/releases/tag/0.0.3) =

* Scrolling Past EOF is possible in normal and vertically split view
* Dynamic adjustments and recalculations on window resizing
* Precise calculation for every open files separately
