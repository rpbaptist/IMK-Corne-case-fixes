# IMK Corne case fixes

This is a README file to address IMK Corne case issues and how to fix them.

## What's the problem?

The [Corne keyboard (crkbd)](https://github.com/foostan/crkbd) PCB is designed to be mirrored. As a result the MCU (pro micro or Elite C usually) sits sligthly more to the right on the left half of the board and the TRRS jack sits slightly lower. Normally this isn't a problem.

The [aluminium case designed by IMKulio](https://imkulio.com/) is designed for the right half of the board and then mirrored. For aforementioned reasons this does not work out well.

### The MCU port

The MCU port causes issues with Elite C specifically. I think the pro micro is okay.
