# MdlToObjConverter
A simple converter from Blizzard’s .mdl to the common .obj format

Please note that the program is far from a polished state and has still some suboptimal sections. 
I am aware that may sections could be done far more elegantly or be better structured. This is merely a little side project I created over the span of a few hours and therefore not all that great in terms of quality.

## Features
The program converts .mdl files to .obj files.

## Known Issues
Since this project was only meant for private use, several problems were left unaddressed during development:

•	The material file (.mtl) might not match the material of the .mdl in some cases. If this error is a problem for you, please contact me and I will take some time to fix it as soon as I can. 

•	All .obj files in the target folder may be overwritten with the one converted last. This error should be fixed in this version, however, there was not too much time for testing. To be safe it would be best to use that folder only for conversion and store the input and output models somewhere else.

•	Lack of a file picker. This is just an inconvenience rather than an issue, but the file path needs to be input as a string: Simply click right of the folder name in bar at the top of your file browser, copy that path into the text field and add the filename. If this is too much of an inconvenience, please let me know and I will add a proper file picker as soon as I can.

•	The program might not start on some devices. Please contact me if that is the case for you as well.

## How to use it
I have provided a pre-built .jar file in this repository. This should run on any device that supports Java SE 12 or higher. Of course, you can compile it yourself (once I have committed the source code at least. I would like to work on it a bit before I do so, so that it is a bit more readable etc.)

## Licence
The project is licensed under the MIT licence. More information can be found in the LICENSE file of this directory. 

## How to contribute
Generally, feel free to expand the project. If you need anything or think that you can improve this version just message me and I will come back to you eventually (I’m not online very often, I have to admit). 

If you need anything feel free to message me.
Have fun with the tool!

Best wishes,
M
