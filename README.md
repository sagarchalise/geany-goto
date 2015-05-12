geany-symbol
============

Alternative symbol browser for geany.

***Features***

* Keybinding to open window
* Filter on type
* '@' and '#' to filter classes and variables
* traversing jumps to symbols

The code base is mostly  **Commander** plugin available on geany-plugins.


$ gcc -c geany-symbol.c -fPIC `pkg-config --cflags geany`

$ gcc geany-symbol.o -o geany-symbol.so -shared `pkg-config --libs geany`


**Copy geany-symbol.so to plugin path**
