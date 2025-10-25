==========================
Plover Regenpfeifer
==========================

Regenpfeifer (German stenography system) support for `Plover <https://github.com/openstenoproject/plover>`__.

For now it only remaps the top S- to Z- but it is planned to add orthography rules in the future.

In the versions lower than 1.0.0, -Z was remapped to -N but this was reverted as described in `this blog post <https://stenoblog.com/regenpfeifer-layout-update/>`__.

The dictionary is generated using the `regenpfeifer repo <https://github.com/mkrnr/regenpfeifer>`__ using `this word list <https://github.com/mkrnr/wortformliste>`__.

Recommended Usage
-----------------

Since the regenpfeifer dictionary will change in the future, it it highly recommended to create a separate dictionary with your own mappings.


Installation
------------


The plugin can be installed via the Plover Plugins Manager.


Special Thanks
--------------

Special thanks to Benoit Pierre, Ted Morin, and Nicholas Markopoulos for providing source code and valuable hints on how to set up the plugin.

License
-------

This plugin is licensed under GPLv3, or any later version.

