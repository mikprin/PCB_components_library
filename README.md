# KiCAD component library

This repository poses as a central storage for KiCAD library files.

## Using this library

Use this repository as a git submodule in your project. This ensures that the relative paths to the files stay the same.

The component libraries for this PCB project are managed as git submodules.

After cloning this repo, you'll need to execute the following commands (inside the repository):

`git submodule init`

`git submodule update`

More info on git submodules: https://git-scm.com/book/en/v2/Git-Tools-Submodules

More info on the library management: https://www.youtube.com/watch?v=oXzJFrLo77Y

## Where to find components

* `passive/` for resistors, capacitors, inductors and filters
* `semi/` for ICs, diodes, LEDs, transistors and crystals
    * `ICs/` are sorted by manufacturer
* `mechanical` for connectors
