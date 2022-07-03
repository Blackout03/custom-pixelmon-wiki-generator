# custom-pixelmon-wiki-generator
A program that can help custom pixelmon datapack creators to automatically log their pixelmon info on wiki.

Run this program with prompt, you'll get pixelmon strings in wiki format.

This program currently cannot process in batch, this feature will be added in future.

Though users can get an entire page frame by processing the `.json` file of a pixelmon, there're still some details need to be edited.

## What DO NOT need to edit
* Pixelmon info boxes(name, form, abilities, weight etc.)
* Pixelmon stats
* Type effectiveness
* Moves in official Pokemon game
* Authors

## What need to be edit
* The previous and the next pixelmon of the current pixelmon
* Pixelmon species
* Pixelmon height (Since the program read the model height from `dimensions`. But model height ≠ real height)
* Pokedex entry
* Pixelmon biology 
* Obtaining ways (W.I.P.)
* Helding items (W.I.P.)
* Custom Moves
* Evolution method (W.I.P.)
* Datas & Resources Download links
