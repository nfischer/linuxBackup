backup
======

A simple backup script for linux (and other unix derivatives) computers.

Compatibility
-------------
This bash script should be compatible over Linux and Mac. It may also
be compatible over other BSD and unix derivatives. This is tested on
Linux mainly. I have also done limited testing on Mac. No testing has
been done on other systems.

Options
-------

```
-f                    backup all files and subdirectories (default is to
                      backup dirs under a threshold size)
-h, --help            display this help menu
-n NAME               put your backup in folder called NAME
-o                    create a backup even if one has already been done that
                      day
-p                    change your backup password
-r, --restore DIR     restore an existing backup DIR
-t                    compress your backup in a .tar.gz archive
```
