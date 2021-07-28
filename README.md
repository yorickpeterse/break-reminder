# Fish Break Reminder

Personal break reminder software, written in Fish.

# Requirements

* Fish
* Cinnamon DE
* aplay
* libnotify

# Usage

Running the timer:

    fish bin/breaks

Using systemd:

    ln -s $PWD/bin/breaks $HOME/bin/breaks
    ln -s $PWD/systemd/breaks.service ~/.config/systemd/user/breaks.service
    systemctl --user start breaks

# License

All source code in this repository is licensed under the Mozilla Public License
version 2.0, unless stated otherwise. A copy of this license can be found in the
file "LICENSE".
