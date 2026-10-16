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

## New in 1.8.0

- **The key backlight also goes out while the uConsole sleeps**, along with
  the trackpad light, when you use
  [jhob101/uconsole-sleep-hack2you-kb-2.1](https://github.com/jhob101/uconsole-sleep-hack2you-kb-2.1).
- **The trackpad light goes out when idle**, with the key backlight, and comes
  back on the next key press or trackpad movement.
- **Using the trackpad keeps the lights on.** Before, only key presses counted
  as activity, so the lights could go out mid-use.

## After you flash

If you use the sleep service, shut the uConsole down and power it back on
before you next sleep it with the power button. A reboot is not enough.
Otherwise the keyboard does not come back when the power button wakes it.

## Before you flash

Back up the firmware you are running now before you flash (copy `CURRENT.UF2`
off the bootloader drive). This is a spare-time project, tested on one
keyboard: flash at your own risk.
