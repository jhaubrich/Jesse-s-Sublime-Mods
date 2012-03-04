I find myself making changes to allot of existing packages. That is all this project is.

What's Here:
-------------
- Extended Molokai, Eiffel, and Plastic.
- *Mediawiki* syntax added from a tmBundle.
- Added Lists to ReStructured_extended.
- Added Verbatim blocks to ReStructured_extended.
- Included *ReStructured_extended*, `thanks chh`_
    - Includes Shell-Unix-Generic-Extended.tmLanguage, Twilight Extended
    - Removed the meta.paragraph.restructuredtext definition, so that normal text will be colored just like all other standard text as defined in the currently used color theme.
    - Added definitions for the ReST directives .. sourcecode:: bash, .. sourcecode:: console, .. sourcecode:: guess and .. sourcecode:: python
    - Added definitions for the ReST directives .. NOTE::, .. ATTENTION:: and .. WARNING::
    - Corrected some regex flaws.
- Included *orgmode*, `thanks theblacklion`_
- My Settings and Keybindings. (I know this shouldn't be checked in, but it's super convenient for me. You probably want to delete these.)

.. _thanks chh: http://www.sublimetext.com/forum/viewtopic.php?f=3&t=5688
.. _thanks theblacklion: https://bitbucket.org/theblacklion/sublime_orgmode/

Install Instructions
--------------------
- copy or clone into ``Sublime Text 2/Packages``. A symbolic link also works ``ln -s ~/src/Jesse-s-Sublime-Mods Sublime\ Text\ 2/Packages``
- ``Shell-Unix-Generic.tmLanguage`` needs to be overwritten with the one here -- copy it over.

**Note:** The settings in my_settings are sourced last and will override your own.

Favorite Packages
-----------------
- **Package Control**
- **SublimeCodeIntel** -- Autocomplete with library lookups
- **Alternative Autocomplete** -- Textmate style tab completion on local variables. Currently Interferes with CodeIntel.
- **SublimeREPL** -- pdb!!
- **Goto Documentation** -- Python help()
- **FileDiffs** -- Diff against the clipboard (surprising how much I use this)
- **Djaneiro**
- **Theme Soda**
- **Abacus**

Todo
----
* Comment the color schemes with their colors codes
* Create a *real* ReSt plugin. Probably another github project.
* Remove all the PINK (gah!) from Monokai's XML -- hard on the eyes, xml needs a subdued color.


