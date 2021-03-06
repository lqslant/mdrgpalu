# mdrgpalu

[![Build Status for Linux and macOS](https://travis-ci.org/emersion/mdrgpalu.svg?branch=master)](https://travis-ci.org/emersion/mdrgpalu)
[![Build status for Windows](https://ci.appveyor.com/api/projects/status/jrl8ecisepu4u32s?svg=true)](https://ci.appveyor.com/project/emersion/mdrgpalu)

Yet another command-line text editor.

## Usage

```shell
make
./mdrgpalu
```

If `xclip` is available, the clipboard will be shared with the system.
Otherwise, an internal clipboard will be used.

Arch users can [install mdrgpalu from the AUR](https://aur.archlinux.org/packages/mdrgpalu-git/).

## Key bindings

Key bindings aim to be simple, stupid.

Keystroke | Effect
----------|-------
<kbd>Ctrl</kbd> + <kbd>Q</kbd> | Quit
<kbd>Ctrl</kbd> + <kbd>W</kbd> | Close file
<kbd>Ctrl</kbd> + <kbd>O</kbd> | Open file
<kbd>Ctrl</kbd> + <kbd>S</kbd> | Save file
<kbd>Ctrl</kbd> + <kbd>X</kbd> | Cut line/selection
<kbd>Ctrl</kbd> + <kbd>C</kbd> | Copy line/selection
<kbd>Ctrl</kbd> + <kbd>V</kbd> | Paste line/selection
<kbd>Ctrl</kbd> + <kbd>A</kbd> | Select all
Arrow | Move selection
<kbd>Shift</kbd> + Arrow | Extend selection
<kbd>Home</kbd>/<kbd>End</kbd> | Go to start/end of line
<kbd>Ctrl</kbd> + <kbd>Home</kbd>/<kbd>End</kbd> | Go to start/end of file
<kbd>Shift</kbd> + <kbd>Home</kbd>/<kbd>End</kbd> | Extend selection to start/end of file
<kbd>Ctrl</kbd> + <kbd>←</kbd>/<kbd>→</kbd> | Jump to previous/next word
<kbd>Ctrl</kbd> + <kbd>↑</kbd>/<kbd>↓</kbd> | Move line
<kbd>Ctrl</kbd> + <kbd>G</kbd> | Go to line:column
<kbd>Ctrl</kbd> + <kbd>L</kbd> | Select line
<kbd>Ctrl</kbd> + <kbd>P</kbd> | Command palette

## License

The Unlicense
