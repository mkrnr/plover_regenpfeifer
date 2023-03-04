==========================
Plover Regenpfeifer
==========================

Regenpfeifer (German stenography system) support for Plover.

For now it only remaps the top S- to Z- but it is planned to add orthography rules in the future.

In the versions lower than 1.0.0, -Z was remapped to -N but this was reverted as described on https://stenoblog.com/regenpfeifer-layout-update/.

The dictionary is generated with the corresponding version of https://github.com/mkrnr/regenpfeifer using the word list from https://github.com/mkrnr/wortformliste.

Recommended Usage
-----------------

Since the regenpfeifer dictionary will change in the future, it it highly recommended to create a separate dictionary with your own mappings.


Installation
------------

To install the cloned git repository, you can run the following command:

Windows

.. code:: powershell

	.\plover_console.exe -s plover_plugins install <path-to-plover-regenpfeifer-git-repo>

Mac

.. code:: bash

	/Applications/Plover.app/Contents/MacOS/Plover -s plover_plugins install <path-to-plover-regenpfeifer-git-repo>


Special Thanks
--------------

Special thanks to Benoit Pierre, Ted Morin, and Nicholas Markopoulos for providing source code and valuable hints on how to set up the plugin.

License
-------

This plugin is licensed under GPLv3, or any later version.

