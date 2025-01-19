# rofi-systemd

A rofi frontend for controlling systemd units.

![2025-01-19_13-16-14_region](https://github.com/user-attachments/assets/4c4cd7e8-ccf1-4756-b8e2-c4137d0c33e1)

## Installation

Download the script and put it somewhere in your `$PATH`.

Depends on `bash`, `rofi`, `systemctl`, `coreutils`, `util-linux`.

## Usage

```
Usage: rofi-systemd [opts] [user|system|all]

Options:
  -h   Show this help message and exit.
  -f   Only show failed units.
  -C   Disable caching.

Control systemd via rofi
```

The script will open a rofi menu with a list of systemd units. 

## TODO

- Configurable keybindings
- Configurable theme
- Ability to start rofi with a specific filter
- AUR package

## License

This project is licensed under the GNU General Public License v3.0.

Based on [IvanMalison/rofi-systemd](https://github.com/IvanMalison/rofi-systemd), which is licensed under the GNU General Public License v3.0.

&copy; 2020 Maddison Hellstrom
&copy; 2018 Ivan Malison
