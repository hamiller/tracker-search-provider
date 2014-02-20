tracker-search-provider
=======================

__Gnome-shell extension__: displays tracker search results in the shell overview


## Description
When in onverview mode of gnome-shell, everytime you enter a string, the shell displays found results for you.
This can be programs, contacts etc.
This extension displays the results, which the tracker framework delivers - obviously, you need a working tracker framework (https://wiki.gnome.org/Projects/Tracker).

It is only invoked, for searches (=string length) above 2 characters.

This extension is derived from https://github.com/cewee/tracker-search.
Since it looks like it was abandoned, I completely refactored it to work again in gnome-shell 3.10 onward.



## Installation
To install, simply copy the 3 files into a directory '~/.local/share/gnome-shell/extensions/tracker-search-provider@sinnix.de'
(the directory 'tracker-search-provider@sinnix.de' has to be created first).
Then reload your shell (you can also logout/login) and acitvate it with gnome-tweak-tool or the extensions website.



Please feel free to contribute (especially for displaying the results itself)
