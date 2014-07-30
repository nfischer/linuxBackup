backup
======

A simple backup script for unix computers.

What can it do?
---------------

This bash script does exactly what it sounds like. This is a quick and
efficient way to back up your personal files. But what makes it special?

This utility differs from others in that it only backs up small directories in your home folder by defaut. This has the following advantages:
    - It's faster
    - Your backup is less cluttered
    - Folders such as your movies directory won't be copied everytime, since they aren't likely to change
    - Critical files such .profile, .vimrc, and .bashrc will be backed up every time

What if this isn't ideal? You can always specify a full backup if you need
to get changes to large folders or files.


