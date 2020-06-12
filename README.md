# Hackman

## What is Hackman ?

Hackman is a Pacman inspired game built to demonstrate the power of the Jack language and the Hack platform.

The Jack language and the Hack platform are both part of a wonderful project called NandToTetris. 

This project is a free course by Noam Nisan and Shimon Schocken on how to build a computer from the ground up.

Find more about Nand2Tetris : https://www.nand2tetris.org/

## License

This project is distributed under the [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)](https://creativecommons.org/licenses/by-nc-sa/3.0/).

## The game

In this game, you play as Hackman, a hack developer trying to eat all the zeros and ones on the map.
Beware of the 3 Phantogates PhantoNand, PhantoXor and PhantoMux that will kill you if they ever catch you.

You can eat the Phantogates for a short time after eating a "1". Use it to your advantage.
 
## About the code

The Jack code of this game is written to be easily understood and maintained, 
and thus it does not strive to achieve minimal ROM footprint nor maximal performance.

Many functions, variables (etc.) exist in an effort to provide a clean architecture.

If you are looking for tips and tricks about perfomance for the hack platform, you could checkout QuesterZen's [Hackenstein3D project](https://github.com/QuesterZen/hackenstein3D).

## Running the game (copied from [Hackenstein3D project](https://github.com/QuesterZen/hackenstein3D))

* Download the .vm files into a single directory.
* Download the Hack VM Emulator from the NAND2tetris website: http://nand2tetris.org.
* Run the VMEmulator from a shell.
* Select 'File > Load' Program from the menu and point to the directory containing the .vm files
* Select 'View > Animate > No Animation' and set the slider to 'Fast'
* Finally press the '>>' button or F5 to run the game.
