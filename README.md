# Yet Another Z-Based Shell

## Requirements
- A CLI (Command-Line Interface), i.e.: a terminal
- `zsh`

## New Commands
- In `yazbsh`, there are two extra commands:
  - `cprint`
  - `about`
- Since this is made in an interpreted language (`zsh`), you do not need to run it through a decompiler. You are able to just edit it on the spot.

### `cprint`
- In `yazbsh`, the command `cprint` is introduced, which is a translation layer for ANSI (e.g.: `\x1b[35;42m`, `\033[36;47m`, etc.)
- Each color has a different letter. An **uppercase** letter changes the *background*, while a **lowercase** letter changes the *foreground*.
    - k/K: black
    - b/B: blue
    - r/R: red
    - w/W: white
    - y/Y: yellow
    - g/G: green
    - c/C: cyan
    - m/M: magenta
- The tag `--no-newline` removes the `\n` at the end of the line, which is useful for making prompts.
