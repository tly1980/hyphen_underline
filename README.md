Hyphen Underline
================

This is a *hyphen to underline* converter plugin for Sublime Text 3
And it is fork from (underliner) [https://github.com/dfleury/underliner]

Motivation
----------

I figured out how boring is write python methods to describe a test case typing
underlines (also called underscore) instead of spaces.
So I made this plugin to replace spaces contained in selected code chunks in a
practical way.

Usage example
-------------

```
a-bb--ccc---dddd
a-bb-ccc_dddd
```

After selecting a text like that above, there are many ways to activate the
Underliner command such: context menu, main menu (`Edit > Convert Case >
Hyphen <> Underline`), command list (`[Ctrl/Cmd]+Shift+P > Convert Case: Hyphen <> Underline`)
and the keyboard shortcut (`[Ctrl/Cmd]+Shift+H`), which is my preferred option.
The expected effect is the same text with each space character replaced to a
underline:

```
a_bb__ccc___dddd
a_bb_ccc_dddd
```
You can do the reverse too. Same principle: select and execute the command.
Spaces and underlines are counted and the most found charactere will be used as
target to replace, maintaining the less found characteres.

License
-------

The MIT License (MIT) - Copyright (c) 2014 Diego Fleury
The MIT License (MIT) - Copyright (c) 2019 Tom Tang
