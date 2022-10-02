# ST - Simple Terminal

ST is a simple terminal emulator for X which sucks less.

This is a fork, the original repo can be found here: [https://git.suckless.org/st/](https://git.suckless.org/st/)
The original st webpage is here: [https://st.suckless.org/](https://st.suckless.org/)

## Requirements

In order to build st you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install

## Running st

If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

#### Keyboard
Action      | Key Combination
---         | ---
Zoom In     | `alt` + `shift` + `M`
Zoom Out    | `alt` + `shift` + `L`
Reset Zoom  | `alt` + `shift` + `O`
Scroll up   | `alt` + `arrow up`
Scroll down | `alt` + `arrow down`

#### Mouse
Action | Modifier
---    | ---
Scroll |  `mouse wheel`

## Credits

* Forked from [https://st.suckless.org/](https://st.suckless.org/)
