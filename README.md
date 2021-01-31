# Nettie's Gamepad Mod for PICO-8 HTML export

A PICO-8 plate that improves gamepad support in HTML exports. Addresses the problems in [this thread on the PICO-8 BBS](https://www.lexaloffle.com/bbs/?tid=41293).

Modified from the PICO-8 0.2.1b HTML template.

# Features

- Full Dpad support.
- Gamepads are only assigned to players when they first press a button. This way if you have multiple gamepads you aren't stuck with whatever order the browser decides to assign them to P1, P2, etc.

# Usage

- Go to the plates folder. (Run `FOLDER` in PICO-8 to open the carts folder, go up one level, the plates folder should be alongside.)
- Copy `netties_gamepad.html` into that folder.
- Load up your game in PICO-8
- Export with `EXPORT YOURGAME.HTML -P NETTIES_GAMEPAD`

