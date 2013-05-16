monkey.sublime-linux
==============

This bundle allow to use [Sublime Text](http://www.sublimetext.com) for Linux as an IDE for the [monkey programming language](http://www.monkeycoder.co.nz) 


monkey.sublime-linux is modification of [monkey.sublime](https://github.com/gingerbeardman/monkey.sublime) created by Matt Sephton.

monkey.sublime-linux support linux only. 

## Installation

- Download zip
- Rename it to monkey.sublime-package
- Put it to Sublime Text 2/Pristine Packages


## Additional info
Your linux trans need to be located in ~/Monkey/bin and named trans_linux
Full path will look like /home/%username%/Monkey/bin/trans_linux

If your trans_linux located in other folder you need to copy it ~/Monkey/bin
mkdir ~/Monkey
mkdir ~/Monkey/bin
cp /path/to/trans_linux ~/Monkey/bin/trans_linux

Or you can edit files Monkey - android.sublime-build, Monkey - flash.sublime-build, Monkey - glfw.sublime-build, Monkey - xna.sublime-build, Monkey - html5.sublime-build, Monkey - ios.sublime-build and Monkey - stcpp.sublime-build.
Just replace ~/Monkey/bin/trans_linux in string "cmd": ["~/Monkey/bin/trans_linux", "-target=Html5_Game", "-run", "\"$file\""], with your path. 
For example: "cmd": ["/usr/bin/trans_linux", "-target=Html5_Game", "-run", "\"$file\""]

## Platforms support
monkey.sublime-linux allow to build html5 games.
build-files for other platform will be corrected and re-uploaded soon. 

## Feautures
Read about monkey.sublime feautures you can on [monkey.sublime page](https://github.com/gingerbeardman/monkey.sublime). 


## Requirements
- Sublime Text 2 [http://www.sublimetext.com/2](http://www.sublimetext.com/2) for Linux
- monkey [http://www.monkeycoder.co.nz](http://www.monkeycoder.co.nz) (linux translator, config.linux, modules, targets).


## License
[Creative Commons Attribution-Share Alike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0).

