# SmallBASIC syntax coloring for NANO

This nano package adds syntax coloring for the SmallBASIC language (https://smallbasic.github.io/).

![Example](https://github.com/Joe7M/smallbasic.nano.syntaxcoloring/blob/main/screenshot.png)

## Installation

- Create a folder `~/.config/nano/syntax`
- Copy the file "smallbasic.nanorc" into that folder
- Edit `nanorc` -> `nano ~/.config/nano/nanorc`
- In the section `## === Syntax coloring ===` add `include "~/.config/nano/syntax/*.nanorc"`

## Tweaking nano

Depending on your Linux distribution the default nano settings are a little bit disappointing.
But fortunately you can tweak nano quite a bit by activating some settings in `nanorc`.
Just remove the comments for:

1. `set autoindent`
2. `set indicator`
3. `set linenumbers`
4. `set minibar`
5. `set mouse`
6. Remove the comments in the section `### Paint the interface elements of nano` to make nano colorful.
7. `include "/usr/share/nano/*.nanorc"`
8. To get more common keyboard shortcuts like CTRL+C for copy uncomment all the commands in the section
   `## If you would like nano to have keybindings that are more "usual"`


## A useful hint

If you use nano in a console you can suspend it by pressing `CTRL-Z`. After pressing `CTRL-Z` you are on the
console and you can i.e. start the console version of SmallBASIC to test your program. After testing
you can switch back to the suspended nano by executing the command `fg` in the console.