I find myself making changes to allot of existing packages. That is all this project is.

Changes made:
~~~~~~~~~~~~~
* Orgmode syntax added to Molokai, Eiffle and Plastic
* Added ReStructured_extended, `thanks chh`_
    - Includes Shell-Unix-Generic-Extended.tmLanguage, Twilight Extended
    - Removed the meta.paragraph.restructuredtext definition, so that normal text will be colored just like all other standard text as defined in the currently used color theme.
    - Added definitions for the ReST directives .. sourcecode:: bash, .. sourcecode:: console, .. sourcecode:: guess and .. sourcecode:: python
    - Added definitions for the ReST directives .. NOTE::, .. ATTENTION:: and .. WARNING::
    - Corrected some regex flaws.
* Lists to ReStructured text
* comment blocks to ReStructured text.


Install Instructions
~~~~~~~~~~~~~~~~~~~~
Copy all the files to where they go. :)
* copy or clone into `Sublime Text 2/Packages`
* `Shell-Unix-Generic.tmLanguage` needs to be overwritten with the one here -- copy it over.

Favorite Packages
~~~~~~~~~~~~~~~~~
* Package Control
* SublimeCodeIntel -- Autocomplete with library lookups
* Alternative Autocomplete -- Textmate style tab completion on local variables
* SublimeREPL -- pdb!!
* Goto Documentation -- Python help()
* FileDiffs -- Diff against the clipboard (suprising how much I use this)
* Djaneiro
* Theme Soda
* Abacus

Todo
~~~~
* Create a *real* ReSt plugin. Probably another github project.
* Remove all the PINK (GAHH) from Monokai's XML -- hard on the eyes, xml needs a subdued color.

.. _thanks chh: http://www.sublimetext.com/forum/viewtopic.php?f=3&t=5688


