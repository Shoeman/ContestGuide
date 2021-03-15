# How to make a contest by Shoe

## Introduction - Where things are

- All files concerned with contest building can be found under the directory:
`C:/Program Files (x86)/BAMZOOKi`

- You will need to have administrator privileges to edit these files

- `C:/Program Files (x86)/BAMZOOKi/Contests/Contest Pack` contains 2 types of file:
  - *.contest* files contain pretty much everything about a given contest. This is what you will work with most when building contests
  - *.png* images which are just the images that you see on the simulator

- `C:/Program Files (x86)/BAMZOOKi/ContestsPacks` contains 1 file, *ContestPack1.dat* which tells the simulator:
  - The contests to be listed
  - Their display names
  - The images they're associated with them
  - some information on what happens to the selected zooks and scores if the contest has them

For a new contest to be listed in the simulator you will need to add a new entry to either ContestPack1.dat or a new .dat file in the same location. I would recommend  the latter to keep any custom contests separate from the originals.

Both the *.dat* and *.contest* files can be opened and edited with most text editors, such as notepad. But there are benefits to using an editor built for code, [Sublime](https://www.sublimetext.com/) and [Notepad++](https://notepad-plus-plus.org/) are both good choices.

The contents of these files use a markup language only used by BAMZOOKi, it's visually similar to [JSON](https://www.json.org/json-en.html), but more closely related to [table syntax in LUA](https://www.lua.org/pil/2.5.html). Don't worry if you haven't heard of either of these as we will be learning it from scratch.

When making edits to a contest that is alreadly listed on the simulator, you only need to save the contest file and re-run the contest to see the changes (no need to restart the simulator).

In summary, a new contest requires:
- A *.contest* file
- An entry in *ContestPack1.dat* or a .dat file in the same location for it to be listed in the simulator
- An image for the simulator

[Part 1 - A Cube](PART1.md)

[Part 2 - More Target Agents (Shapes)](PART2.md)

[Part 3 - The Table](PART3.md)
