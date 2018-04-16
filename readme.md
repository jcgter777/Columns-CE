Columns CE -- A Columns clone for the TI-84 CE graphing calculator
==================================================================
Warning:
* **This only works on the TI-84+ CE.**
* This will **not** work on the TI-84+ CSE.
* This will **not** work on any TI-84+ (SE)

Motivation
----------
Because I enjoyed the game on the Sega Genesis when I was much younger
and I wanted something like it on the CE.

Building the Game From Source
-----------------------------
* If you don't have it, install the latest version of the CE C SDK
  from here: https://github.com/CE-Programming/toolchain/releases
* Run `convpng` in the `src/gfx` directory (where `convpng.ini` is) from the
  command-line without any parameters. This will build all the graphics.
* Run `make` from the project's root directory to build the project.
* If all is successful, a `bin` folder should have appeared with at least one
  file named `COLUMNCE.8xp` in it. This is the file you want to send to your
  calculator.
  
Running the Game
----------------
* Send `COLUMNCE.8xp` to your TI-84 CE graphing calculator by using your
  favorite computer-to-calculator link software (e.g. TiLP, TI-Connect CE).
* If you do not have the 'Standard' CE libraries (`GRAPHX`, `FILEIOC`, etc.),
  you should download them from
  https://tiny.cc/clibs and also send them to
  your calculator.
* Run the program...
  * ...by using your favorite shell software (e.g. DoorsCE9, Cesium, etc.)
    * Follow the instructions provided by that software on how to run Columns CE.
  * ...by invoking it on the homescreen as an ASM program. To do this:
    * `CLEAR` the homescreen
	* Bring up the catalog by pushing <kbd>2nd</kbd>, then <kbd>0</kbd>
	* Arrow down until you select `Asm(`, then push <kbd>enter</kbd>
	* Push <kbd>prgm</kbd> and (if needed) scroll down until you select `COLUMNCE`,
	  then push <kbd>enter</kbd>
	* You should see on the homescreen `Asm(prgmCOLUMNCE`. Push <kbd>enter</kbd> to run.
	
Troubleshooting
---------------
TODO later. Follow all onscreen prompts and you should be fine.

Controls
--------
In the menu:

| Keys     |  Function         |
|---------:|:------------------|
|<kbd>mode</kbd>    | Go back/Quit      |
|<kbd>2nd</kbd>     | Select option     |
|Arrow keys| Change menu option|

During gameplay:

| Keys       |  Function                |
|-----------:|:-------------------------|
|<kbd>mode</kbd>      | Forfeit/Quit             |
|<kbd>2nd</kbd>       | Shift the jewels         |
|<kbd><</kbd>/<kbd>></kbd>| Move jewels left or right|
|<kbd>v</kbd>      | Quickly drop the jewels  |

License and Copyright
---------------------
* The graphics are copyrighted to SEGA. Used without permission.
* The program is covered under the terms of the MIT license, found in `LICENSE`










