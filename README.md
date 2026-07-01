
# First Aid Plugin for KADAS

## How to use locally 

1) Get the source code using git 

`git clone https://github.com/kadas-albireo/kadas-mbtiles-plugin.git`

2) Create a link from the kadas plugin folder to your local repository folder

e.g : `mklink /J C:\Users\Valentin\AppData\Roaming\Kadas\Kadas\profiles\default\python\plugins\firstaid C:\Users\Valentin\Documents\kadas-albireo\kadas-first-aid-plugin\firstaid`

> Note:  link might differ on other OS than windows

3) In the tab settings next to the plugin manager there is a new button Debug to access the first aid plugin



# First Aid Plugin for QGIS

<img src="https://raw.githubusercontent.com/wonder-sk/qgis-first-aid-plugin/master/icon.png" align="right">

The plugin adds a debugger for Python code that runs with QGIS - making it super easy to trace any plugin.
It supports all the usual features from other debuggers - set breakpoints, inspect variables, step into/over
code etc.

It also replaces the default Python error handling in QGIS
with a more sophisticated handler that allows more thorough inspection
or the Python error: browse the frames, view variables, see source code
or even execute Python code within the context of the error.


## How to use it?

Simply install the plugin and enable it. The custom error handler is registered automatically.
In order to start the debugger, look for Debug icon in Plugins toolbar - or press F12 (Note: since
version 2.1.4 this is Ctrl+F12 because F12 is used by development tools dock in QGIS >= 3.14). A new window
will pop up where you can open files and set breakpoints. Debugging is active all the time while
the debugger window is open. Once a breakpoint is reached, debugger window will be activated
and ready to step through the code.


## First Aid in Action

Debugger:

<img src="https://raw.githubusercontent.com/wonder-sk/qgis-first-aid-plugin/master/screenshot-debug.png">

Custom Python error handler:

<img src="https://raw.githubusercontent.com/wonder-sk/qgis-first-aid-plugin/master/screenshot.png">


## License

Licensed under the terms of GNU GPL 2.

