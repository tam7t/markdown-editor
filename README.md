Markdown Editor
==========
(C) 2013 [tam7t](http://www.ourbunny.com)

This is a markdown editor.  There are many like it but this one is mine.  It has many features:

1. Editing markdown
2. Edit preview CSS
3. Preview markdown

It can even open and save files! That is about it.

***Warning: *** This was built as an exercise with Python, Qt, and PySide. **No input validation** is performed, leaving it open to all sorts of fun/risk. It might even be fun to just use this as an exercise on how to hack/break something.

Libraries
-------
* [Python-Markdown](https://github.com/waylan/Python-Markdown) (BSD)
* [PySide](http://qt-project.org/wiki/Category:LanguageBindings::PySide) (LGPL v2.1) 
* [Qt](http://qt-project.org) (LGPL v2.1) 
* [css](https://gist.github.com/andyferra/2554919) (unknown)

Install
-----
Follow the instructions for installing PySide and Qt from the PySide website.  If using OSX be sure to have at least:

* Python 2.7.3
* PySide 1.1.1
* Qt 4.8.0

Install python-markdown either to your system or save the "markdown" folder at the same level as the script.

Then just...

	python markdown-editor.py

and look at it go!