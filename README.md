![Introduction banner: a solitary syrup pump where midday light lands earliest on a fountain counter, ledgers and ticket rolls spaced behind it, brass scales and shelving in the far zone, no writing anywhere](intro-banner.png)

# dm-data-type-converter

Day book entry, ruled columns: the name above is set in Carattere in shelf wood, with a small tag sketch at the left of this title block and the syrup pump drawn small beside this first heading only. Every other heading on this page keeps the day book treatment without pictures, so a long page stays quick to scan.

![Logo](logo.png)

![Banner](banner.png)

![Animated scene: three bands of a fountain counter. Far band, shelving fixed to the wall and a brass scale beam tipping once under a placed weight, then settling level. Middle band, a hand pulling one ticket from a roll, tearing it at the perforation, spiking it. Near band, a hand pressing a cocked pump handle down once, filling a glass, finishing with a wrist flick](scene.svg)

![Major separator: measuring tape unreeling across the counter](sep-heavy.svg)

# dm-data-type-converter
Converts data from one format to another to obscure the original value. For example, converts integers to hexadecimal representations, or strings to base64 encoded values. Can also randomly select from a set of conversion methods. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

> Day book note, twine edge: integers become hexadecimal representations.

> Day book note, twine edge: strings become base64 encoded values.

> Day book note, twine edge: the program can randomly select a method.

> Day book note, twine edge, corrected in this wave: the -m flag formerly carried no description; it now carries its four choices and random default.

![Major separator: measuring tape unreeling across the counter](sep-heavy.svg)

## Two Named Conversions

Conversion cards at this counter carry a small pump handle silhouette at the top corner, handle cocked. Whole numbers arrive at the pump and leave wearing hexadecimal dress, the same quantity in another costume. Letter strings arrive and leave as base64 encoded values, the same letters inside with no letters showing. A third card stands for the house choice: the program can randomly select from a set of conversion methods, and the set itself is listed nowhere in this record.

Field on the counter card: Conversion Method

[Convert the Values](#parameters)

![Minor separator: a short centred length of measuring tape](sep-light.svg)

## Install
`git clone https://github.com/ShadowGuard-AI/dm-data-type-converter`

> Day book note, twine edge, corrected in this wave: the clone line formerly named an older organisation; it now names ShadowGuard-AI.

![Minor separator: a short centred length of measuring tape](sep-light.svg)

## Usage
`python3 main.py DATA [-m METHOD]`

One line orders everything: data is the input, and the converted data prints to stdout. This record still prints no worked example call.

![Minor separator: a short centred length of measuring tape](sep-light.svg)

## Parameters
- `data`: The data to convert. Required.
- `-h`: Show help message and exit
- `-m`, `--method`: The conversion method to use. Choices: hex, base64, md5, random. Defaults to random.

![Minor separator: a short centred length of measuring tape](sep-light.svg)

## One Flag, Described

Past help, the control list is one flag plus the required data positional, and that flag is now described in the parameter list above.

The set of conversion methods is now listed in the parameter list above: hex, base64, md5, and random, beyond the two named conversions. There is still no guard paragraph: refusal behaviour is undocumented here, and output goes to stdout, not to a file control.

![Major separator: measuring tape unreeling across the counter](sep-heavy.svg)

## License
This project is released under the license in the [LICENSE](LICENSE) file. See LICENSE for details.

> Day book note, twine edge, corrected in this wave: the closing line formerly named the older organisation; it now points at LICENSE.
