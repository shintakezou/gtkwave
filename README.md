# gtkwave

Import of gtkwave 3.3.104 from sourceforge.

See it on [guix.gnu.org](https://guix.gnu.org/packages/gtkwave-3.3.104/), where it links to [sourceforge](http://gtkwave.sourceforge.net/) as the site.

## Why?

Why not? (It weren't on github, so I couldn't fork it. Maybe github is not good for GNU and libre projects…?)

## Changes

There's [a branch](https://github.com/shintakezou/gtkwave/tree/signals-heights) containing a quick ugly change: a new integer paramenter, `signal_height_mag`, can be used to specify how much you want to magnify the signals' heights. Default 100 means ×1; a value of 200 would mean ×2, and so on: the magnify factor is the integer value/100. It works, but signals' names are not well positioned in the bigger available area.

## Original README

Read the [original_README](original_README).


## License

Read the [Original license](original_LICENSE.txt). The excerpt shown below clarifies that the [LICENSE](LICENSE) included should be ok:

> This program is free software; you can redistribute it and/or modify it
> under the terms of the GNU General Public License as published by the Free
> Software Foundation; either [version 2 of the License](LICENSE), or (at your option)
> any later version.

