# sudoku

The scope of this project is to create a programme that recognizes a sudoku puzzle off a photo, extracts all the information from the puzzle and outputs it in a more convinient file format that could be uploaded to sudoku-solver web-interfaces such as Sven's Sudoku pad.


## Planned workflow:

On sudoku detection:
- build capabilities to detect outer grid, horizontal/vertical lines and digits on a digital ("regular") image of a sudoku puzzle.
- expand detection capabilitites to on-paper photos of sudoku puzzles with only printed numbers
- expand detection capabilities to hand-written digits in digital puzzles
- expand detection capabilitioes to on-paper partly-handwritten.

On the sudoku interface/file:
- research existing file formats for sudokus
- build an interface for Sudoku objects
- create a function that exports a sudoku object into a friendly file-format
- display sudoku files in web
- find a way to import sudoku files into Sven's sudoku pad



