Firmware for the hack2you uConsole trackpad keyboard, **V2.1**.

## Which file

| File | What is different |
| --- | --- |
| `bb9900-zmk.uf2` | The standard firmware. Pressing the trackpad is a left click and a tap on B is a middle click. |
| `bb9900-zmk-middle-click.uf2` | Those two swapped: pressing the trackpad is a middle click and a tap on B is a left click. |
| `bb9900-zmk-one-handed.uf2` | The [one-handed layout](https://github.com/jhob101/uconsole-bb9900-keyboard#one-handed-layout): Y middle click, B right click, X a scroll switch, A F11. |

Download one and follow the
[flashing instructions](https://github.com/jhob101/uconsole-bb9900-keyboard#flashing).
What every key does is in the
[README](https://github.com/jhob101/uconsole-bb9900-keyboard#what-it-does).

## New in 1.6.0

- **Trackpad light on/off with Fn + `/`.** The choice is remembered. The light
  also goes off while the keyboard is locked.
- **One-shot modifiers are easier to get out of.** Tap one again to cancel it.
  A click or a scroll now uses it up, as a key press does, so a stray Shift no
  longer turns every scroll sideways.

## Before you flash

Back up the firmware you are running now before you flash (copy `CURRENT.UF2`
off the bootloader drive). This is a spare-time project, tested on one
keyboard: flash at your own risk.
